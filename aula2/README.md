# Aula 2 

Nessa aula, abordaremos os seguintes tópicos:
- Rodar um full-node bitcoin
- Visualizar broadcasting de transações, tentativas de mineração/validação


## Rede bitcoin-regtest

### Configuração

1. Instale Docker Community Edition
      
      https://www.docker.com/community-edition
      

2. Faça a instalação do Bash
      
      https://www.howtogeek.com/249966/how-to-install-and-use-the-linux-bash-shell-on-windows-10/

3. Faça o download no github do projeto da aula 2
      
      https://github.com/teogenesmoura/lawBlockchainClass

4. Abra um terminal bash e entre na pasta do projeto
    
    Utilize o comando cd para navegar entre os diretórios.
    Supondo que o arquivo foi descompactado na pasta Downloads utilize o comando: 
          
          cd ~/Downloads/lawBlockchainClass/aula2

5. No diretório ~/Downloads/lawBlockchainClass/aula2 execute os comandos:
          
          make build
          make satoshi

Após esses passos iremos estar em um terminal ubuntu como usuário root no host satoshi.

Repita os passos 4 e 5 em outro terminal e substitua o comando make satoshi por make nakamoto.

### Utilizando a rede bitcoin-regtest

Utilize os seguintes comandos nos dois terminais.

1. Iniciando um fullnode
      
      btc_start

2. Iniciando uma conexão com um peer da rede:
      
      btc addnode IP onetry

      Substitua IP pelo ip do peer.

3. Criando uma carteira

      btc_walletcreate

4. "Minere" alguns bitcoins
      
      btc_generate WALLET_ADDR
  
      Substitua WALLET_ADDR pelo endereço da sua carteira gerado em 3.

5. Verificando seu saldo de bitcoins

      btc_walletinfo
      
    Informações sobre a carteira:
    
      - balance => "saldo da carteira"
      - unconfirmed_balance => total de bitcoins das transasões que ainda não foram confirmadas
      - immature_balance => total de bitcoins que foram "dados" por encontrar um bloco. Só podem ser utilizados depois que 100 blocos forem minerados após ser incluído no blockchain. (Transações CoinBase)

6. Transferindo bitcoins para outra carteira


      btc_tranfer WALLET_ADDR

      Substitua WALLET_ADDR pelo endereço da carteira que receberá os bitcoins



### Comandos

- btc_start
    
    Inicia um fullnode.

- btc_con 
    
    Inicia conexão com o peer inicial da rede P2P

- btc_networkinfo
    
    Informação sobre peers conectados

- btc_walletcreate
    
    Cria uma nova carteira bitcoin. Após executar o comando será mostrado o endereço da carteira

- btc_walletinfo
    
    Informações sobre a carteira:
      - balance => "saldo da carteira"
      - unconfirmed_balance => total de bitcoins das transasões que ainda não foram confirmadas
      - immature_balance => total de bitcoins que foram "dados" por encontrar um bloco. Só podem ser utilizados depois que 100 blocos forem minerados após sua inclusão no blockchain

- btc_walletaddr
    
    Endereço da carteira

- btc_transfer WALLET_ADDR
    
    Transferir bitcoins para um endereço.

    Substitua WALLET_ADDR pelo endereço da carteira que irá receber os bitcoins.

- btc_generate WALLET_ADDR
    
    Gerar alguns bitcoins para uma carteira.

    Substitua WALLET_ADDR pelo endereço da wallet que deseja transferir os bitcoins gerados.
