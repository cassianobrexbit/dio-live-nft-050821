# DIO Pro - Live 05/08/21 - Criando um NFT na Blockchain da Rede Ethereum

Repositório para a Live Coding do dia 05/08/2021

## Configurações inciais

- Instalar o gerenciador de carteiras Metamask: https://metamask.io/
- Obter ethereum faucet para utilizar a testnet Ropsten: https://faucet.ropsten.be/
- Instalar o IPFS: https://ipfs.io/#install

## Enviando arquivos para o IPFS

- Criar repositório IPFS: ```ipfs init```
- Iniciar o IPFS Daemon: ```ipfs daemon```
- Enviando uma imagem para o IPFS: ```ipfs add <DIONFT.png>```
  - Copiar o hash gerado e concatenar à seguinte URL: https://ipfs.io/ipfs/ no arquivo *DIONFT.json* (Ex: https://ipfs.io/ipfs/<ipfs_hash>)
- Enviar o arquivo *DIONFT.json* para o IPFS: ```ipfs add DIONFT.json```

## Desenvolvendo o smart contract

 - Abrir o Remix IDE em https://remix.ethereum.org/
 - Na pasta *contracts*, criar um novo arquivo chamado *DIONFT.sol* e copiar e colar o conteúdo do arquivo *DIONFT.sol* deste repositório
 - Compilar e realizar o deploy em testnet.
