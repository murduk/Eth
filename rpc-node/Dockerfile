FROM ethereum/client-go:v1.10.25

WORKDIR /root/data

COPY ./testnetwork.json ./
COPY rpc-node/keystore  ./keystore

RUN geth init --datadir /root/data /root/data/testnetwork.json