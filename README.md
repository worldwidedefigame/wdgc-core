World Wide Defi Game - Staging Repository (Wdgc Core-v1.0.0)
===========================


What is Wdgc Core?
-------------

Wdgc Core is an experimental digital currency that enables instant, private
payments to anyone, anywhere in the world. Wdgc Core uses peer-to-peer technology
to operate with no central authority: managing transactions and issuing money
are carried out collectively by the network.

Users hold the crypto keys to their own money and transact directly with each other, 
with the help of a P2P network to check for double-spending. Wdgc Core is the 
name of the open source software which enables the use of this currency.

For more information, as well as an immediately useable, binary version of
the Wdgc Core software, see https://koichain.io


Coin Properties
-------------

- Coin name: World Wide Defi Game (Wdgc)
- Coin abbreviation: WDG
- Algorithm: X11 (PoW & Masternode)
- Block size: 3 MB (~1,440 Blocks/Day)
- Block rewards: 1500 WDG/Block
- Block halving: 512500 blocks
- Total premine: 50,000,000 WDG
- Coin supply: 2,100,000,000 WDG


Advanced Properties
-------------

- Masternode reward: 50%
- Masternode amount: 30,000,000 WDG
- Masternode confirmations:	15 blocks
- Coinbase maturity: 20 ( + 1 default confirmation) blocks
- Target spacing: 1 minutes
- Target timespan: 5 minutes
- Transaction confirmations: 6 ( + 1 default confirmation) blocks
- Last block with reward: 19475000
- Time until last block	37 years, 0 months, 10 days, 7 hours


Setup & Running
---------------------
WDGC Core is the original WDGC client and it builds the backbone of the network.
However, it downloads and stores the entire history of WDGC transactions;
depending on the speed of your computer and network connection, the synchronization
process can take anywhere from a few hours to a day or more.

The following are some helpful notes on how to run WDGC on your native platform.

### Unix

Unpack the files into a directory and run wdgc-qt (GUI, 64-bit) or wdgcd (headless, 64-bit).

### Windows

Unpack the files into a directory, and then run wdgc-qt.exe (GUI, 32/64-bit).

### OSX

Drag wdgc-qt to your applications folder, and then run wdgc-qt (GUI) or wdgcd (headless).

### Configuration ./wdgc/wdgc.conf

rpcuser=rpc_wdgc</br>
rpcpassword=1Zqeq5LdRAer3KaJzY9J2Wxe</br>
rpcbind=0.0.0.0</br>
rpcallowip=127.0.0.1</br>
port=36834</br>
rpcport=36833</br>
listen=1</br>
server=1</br>
txindex=1</br>
daemon=1</br>
addnode=node1.koichain.io</br>
addnode=node2.koichain.io


License
-------

Wdgc Core is released under the terms of the MIT license. See [COPYING](COPYING) for more
information or see https://opensource.org/licenses/MIT.
