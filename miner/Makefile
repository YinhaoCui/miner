all: miner

HDR=siggen.h mempool.h transactions.h nonce.h

SRC=main.c siggen.c mempool.c transactions.c nonce.c 

miner: $(SRC) $(HDR)
	gcc -Wall -o miner $(SRC) -l pthread

