# Aula 1

Nessa aula, abordaremos os seguintes tópicos:
- Rodar um full-node bitcoin
- Visualizar broadcasting de transações, tentativas de mineração/validação


## Rede bitcoin-regtest

### Docker

#### Faça o download do Docker Community Edition e instale-o
      https://www.docker.com/community-edition

#### Faça o download no github do projeto da aula 2
      https://github.com/teogenesmoura/lawBlockchainClass

#### Descompacte projeto

#### Abra um terminal e entre na pasta do projeto
    Utilize o comando cd para navegar entre os diretórios
    Sumpondo que o arquivo foi descompactado na pasta Downloads utilize o comando: 
          cd ~/Downloads/lawBlockchainClass/aula2

#### No diretório ~/Downloads/lawBlockchainClass/aula2 execute os comandos:
          make build
          make satoshi_shell
  
  Após esses passos iremos estar em um terminal ubuntu como usuário root no host satoshi

### Executando um fullnode em uma rede bitcoin-regtest


#### Inicie o fullnode

    Execute os seguintes comandos:
  
      btc_start
      btc_con

#### Crie uma carteira

      btc_walletcreate

#### "Minere" alguns bitcoins
  
      btc_generate ENDEREÇO_CARTEIRA
  
Substitua ENDEREÇO_CARTEIRA pelo endereço da sua carteira gerado no passo anterior

#### Verifique seus bitcoins

      btc_walletinfo
      
Informações sobre a carteira:
  balance => "saldo da carteira"
  unconfirmed_balance => total de bitcoins das transasões que ainda não foram confirmadas
  immature_balance => total de bitcoins que foram "dados" por encontrar um bloco. Só podem ser utilizados depois que 100 blocos forem minerados após sua inclusão no blockchain

#### Transfira bitcoins para outra carteira

      btc_tranfer ENDEREÇO_CARTEIRA

Substitua ENDEREÇO_CARTEIRA pelo endereço da carteira que receberá os bitcoins



### Comandos

#### btc_start
    Inicia um fullnode.

#### btc_con 
    Inicia conexão com um peer inicial da rede P2P

#### btc_networkinfo
    Informação sobre peers conectados

#### btc_walletcreate
    Cria uma nova carteira bitcoin. Após executar o comando será mostrado o endereço da carteira

#### btc_walletinfo
    Informações sobre a carteira:
      balance => "saldo da carteira"
      unconfirmed_balance => total de bitcoins das transasões que ainda não foram confirmadas
      immature_balance => total de bitcoins que foram "dados" por encontrar um bloco. Só podem ser utilizados depois que 100 blocos forem minerados após sua inclusão no blockchain

#### btc_walletaddr
    Endereço da carteira

#### btc_transfer ADDR
    Tranfere bitcoins para um endereço
    Substitua ADDR pelo endereço da carteira que irá receber os bitcoins

#### btc_generate WALLET_ADDR
    Gera alguns bitcoins para uma carteira
    Substitua WALLET_ADDR pelo endereço da wallet que deseja transferir os bitcoins gerados      

# OBS



    

