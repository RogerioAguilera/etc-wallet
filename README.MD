# Criando carteira BTC na Testnet

- Instalação
npm i bip39 bip32@2.0.6 bitcoinjs-lib --save

- Caso tenha erro na execução da criação da carteira:

**Linux**
* export NODE_OPTIONS=--openssl-legacy-provider

**Windows**
* $env:NODE_OPTIONS="--openssl-legacy-provider"

- Execute novamente o node {{arquivoDeExecucao}}
