# FixedRotor ( big thanks to phriuts / keyhunt cuda dev and all

sudo apt-get install libgmp3-dev libmpfr-dev
sudo apt-get install build-essential

build

thats for cuda 12 if you have another version u can edit Makefile

make gpu=0 CCAP=86 all ( thats for A10 and CCAP=80 for A100 )
edit send.py to ur bot details to get result to telegram : enjoy <3
