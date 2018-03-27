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
RUN echo "alias getpeerinfo='bitcoin-cli -regtest getpeerinfo'" >> ~/.bash_aliases
RUN echo "alias walletcreate='bitcoin-cli -regtest getnewaddress'" >> ~/.bash_aliases
RUN echo "alias wallet='bitcoin-cli -regtest getwalletinfo'" >> ~/.bash_aliases
RUN echo "alias walletaddr='bitcoin-cli -regtest listaddressgroupings'" >> ~/.bash_aliases
RUN echo "alias send='bitcoin-cli -regtest sendtoaddress'" >> ~/.bash_aliases
RUN echo "alias generate='bitcoin-cli -regtest generatetoaddress 1000'" >> ~/.bash_aliases



