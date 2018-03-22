### Aula 1

Nessa aula, abordaremos os seguintes tópicos:
- Rodar um full-node bitcoin
- Visualizar broadcasting de transações, tentativas de mineração/validação

### Docker

Faça o download do Docker Community Edition e instale-o
      https://www.docker.com/community-edition

## Rede bitcoin-regtest

- Faça o download no github do projeto da aula 2
      https://github.com/teogenesmoura/lawBlockchainClass

- Descompacte projeto

- Abra um terminal e entre na pasta do projeto
    Utilize o comando cd para navegar entre os diretórios
    Sumpondo que o arquivo foi descompactado na pasta Downloads utilize o comando: 
          cd ~/Downloads/lawBlockchainClass/aula2

- No diretório ~/Downloads/lawBlockchainClass/aula2 execute os comandos:
          make build
          make satoshi_shell
          bitcoind -regtest -daemon -printtoconsole

    

