FROM ethereum/client-go:v1.10.25

WORKDIR /root/data

COPY ./testnetwork.json ./
COPY keystore  ./
COPY ./password.txt ./

RUN geth init --datadir /root/data /root/data/testnetwork.json