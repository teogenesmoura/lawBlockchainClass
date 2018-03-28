FROM ubuntu:xenial

RUN apt-get -y update
RUN apt-get install -y python-software-properties 
RUN apt-get install -y software-properties-common

RUN add-apt-repository ppa:bitcoin/bitcoin
RUN apt-get update
RUN apt-get install -y iproute2
RUN apt-get install -y vim
RUN apt-get install -y bitcoind

RUN mkdir ~/.bitcoin
RUN echo "rpcuser=test\nrpcpassword=test\n" > ~/.bitcoin/bitcoin.conf

RUN echo "alias btc='bitcoin-cli -regtest'" >> ~/.bash_aliases
RUN echo "alias btc_start='bitcoind -regtest -daemon -printtoconsole'" >> ~/.bash_aliases
RUN echo "alias btc_con='bitcoin-cli -regtest addnode 192.168.0.145:18444 onetry'" >> ~/.bash_aliases
RUN echo "alias btc_networkinfo='bitcoin-cli -regtest getpeerinfo'" >> ~/.bash_aliases
RUN echo "alias btc_walletcreate='bitcoin-cli -regtest getnewaddress'" >> ~/.bash_aliases
RUN echo "alias btc_walletinfo='bitcoin-cli -regtest getwalletinfo'" >> ~/.bash_aliases
RUN echo "alias btc_walletaddr='bitcoin-cli -regtest listaddressgroupings'" >> ~/.bash_aliases
RUN echo "alias btc_transfer='bitcoin-cli -regtest sendtoaddress'" >> ~/.bash_aliases
RUN echo "alias btc_generate='bitcoin-cli -regtest generatetoaddress 2'" >> ~/.bash_aliases



