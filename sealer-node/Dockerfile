FROM ethereum/client-go:v1.10.25

WORKDIR /root/data

COPY ./testnetwork.json ./
COPY sealer-node/keystore  ./keystore
COPY sealer-node/password.txt ./

RUN geth init --datadir /root/data /root/data/testnetwork.json