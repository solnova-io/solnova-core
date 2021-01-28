Solnova Core Staging Repository (Version 1.0.0)
===========================

What is Solnova Core?
-------------

Solnova is an experimental digital currency that enables instant, private
payments to anyone, anywhere in the world. Solnova uses peer-to-peer technology
to operate with no central authority: managing transactions and issuing money
are carried out collectively by the network.

Users hold the crypto keys to their own money and transact directly with each other, 
with the help of a P2P network to check for double-spending. Solnova Core is the 
name of the open source software which enables the use of this currency.

For more information, as well as an immediately useable, binary version of
the Solnova Core software, see https://core.solnova.io


Solnova Specification
-------------

- Coin Name: Solnova Coin (Ticker: SNV)
- Algorithm: X11 (PoW & Masternode)
- Block Size: 3 MB (~1,440 Blocks/Day)
- Block Rewards: 01 SNV/Block (PoW: 50%, Masternode: 50%)
- Pre-Mined: ~13.8% (Total 5,000,000 SNV)
- Max Supply: 36,000,000 SNV


Setup & Running
---------------------
Solnova Core is the original Solnova client and it builds the backbone of the network.
However, it downloads and stores the entire history of Solnova transactions;
depending on the speed of your computer and network connection, the synchronization
process can take anywhere from a few hours to a day or more.

The following are some helpful notes on how to run Solnova on your native platform.

### Unix

Unpack the files into a directory and run solnova-qt (GUI, 64-bit) or solnovad (headless, 64-bit).

### Windows

Unpack the files into a directory, and then run solnova-qt.exe (GUI, 32/64-bit).

### OSX

Drag solnova-qt to your applications folder, and then run solnova-qt (GUI) or solnovad (headless).


License
-------

Solnova Core is released under the terms of the MIT license. See [COPYING](COPYING) for more
information or see https://opensource.org/licenses/MIT.
