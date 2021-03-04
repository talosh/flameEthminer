# flameEthminer
Etherium miner compiled to run on Autodesk Flame linux system

* Download it from releases and unpack
* If you don't have Etherium wallet yet create one:
```
  ./geth account new
```
* New wallet is the number like this:
```
Public address of the key:   0x331144A46b44D515348A5b7e11a274b49ec9cb88
```
* Find a server close to you:

| Location | Server Host |
| -------- | ----------- |
| Europe | eth-eu1.nanopool.org |
| Europe | eth-eu2.nanopool.org |
| US East | eth-us-east1.nanopool.org |
| US West | eth-us-west1.nanopool.org |
| Asia | eth-asia1.nanopool.org |
| Japan | eth-jp1.nanopool.org |
| Australia | eth-au1.nanopool.org |

* Go mining:
```
./ethminer -P stratum1+tcp://0x<paste_your_number_here>.Flame@<closest_server_name>.nanopool.org:9999
```
* More info: https://github.com/ethereum-mining/ethminer#examples-connecting-to-pools
* Source code: https://github.com/ethereum-mining/
