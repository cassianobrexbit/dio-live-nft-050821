# DIO Pro - Live 05/08/21 - Criando um NFT na Blockchain da Rede Ethereum

Repositório para a Live Coding do dia 05/08/2021

## Configurações inciais

- Instalar o gerenciador de carteiras Metamask: https://metamask.io/
- Obter ethereum faucet para utilizar a testnet Ropsten: https://faucet.ropsten.be/
- Instalar o IPFS: https://ipfs.io/#install

## Enviando arquivos para o IPFS

- Criar repositório IPFS: ```ipfs init```
- Iniciar o IPFS Daemon: ```ipfs daemon```
- Enviando uma imagem para o IPFS: ```ipfs add <file.ext>```
  - Copiar o hash gerado e concatenar à seguinte URL: https://ipfs.io/ipfs/ no arquivo dioNFT.json (Ex: https://ipfs.io/ipfs/<ipfs_hash>)
- Enviar o arquivo dioNFT.json para o IPFS: ```ipfs add dioNFT.json```

## Desenvolvendo o smart contract

 - Abrir o Remix IDE em https://remix.ethereum.org/
 - Na pasta Contrats, criar um novo arquivo chamado dioNFT.sol e copiar e colar o conteúdo do arquivo DIONFT.sol
 - Compilar e realizar o deploy em testnet.
