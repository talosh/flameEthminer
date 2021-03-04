# flameEthminer
Etherium miner compiled to run on Autodesk Flame linux system

* Download it from releases and unpack
* If you don't have Etherium wallet yet create one:
```
  ./geth account new
```
* New wallet id is the number like this:
```
Public address of the key:   0x331144A46b44D515348A5b7e11a274b49ec9cb88
```
* Go mining:
```
./ethminer -P stratum1+tcp://0x<paste_your_number_here>.Flame@eth-eu2.nanopool.org:9999
```
* More info: https://github.com/ethereum-mining/ethminer#examples-connecting-to-pools
* Source code: https://github.com/ethereum-mining/
