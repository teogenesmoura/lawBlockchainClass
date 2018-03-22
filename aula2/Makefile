#Adaptado de https://github.com/gak/docker-bitcoin-regtest

DOCKER_RUN=sudo docker run -t
DOCKER_SATOSHI	=$(DOCKER_RUN) -p 18444:18444 -p 18332:18332 --name=satoshi --hostname=satoshi
DOCKER_NAKAMOTO =$(DOCKER_RUN) -p 19444:18444 -p 19332:18332 --name=nakamoto --hostname=nakamoto

IMG=aula2/bitcoin-regtest

RUN_DAEMON=bitcoind -regtest -rpcallowip=0.0.0.0/0 -printtoconsole
RUN_SHELL=bash

build:
	sudo docker build -t aula2/bitcoin-regtest bitcoin-regtest

satoshi_rm:
	-sudo docker rm -f satoshi 

nakamoto_rm:
	-sudo docker rm -f nakamoto

satoshi_daemon: build satoshi_rm 
	$(DOCKER_SATOSHI) -d=true $(IMG) $(RUN_DAEMON)

satoshi_shell: build satoshi_rm
	$(DOCKER_SATOSHI) -i $(IMG) $(RUN_SHELL)

nakamoto_daemon: build nakamoto_rm
	$(DOCKER_NAKAMOTO) -d=true $(IMG) $(RUN_DAEMON)

nakamoto_shell: build nakamoto_rm
	$(DOCKER_NAKAMOTO) -i $(IMG) $(RUN_SHELL)
