naturacoin 1.7
=====================

* Copyright (c) 2009-2014 Bitcoin Developers
* Copyright (c) 2011-2013 Litecoin Developers
* Copyright (c) 2013-2014 naturacoin Developers


Setup
---------------------
[naturacoin Core](http://naturacoin.com/en/download) is the original naturacoin client and it builds the backbone of the network. However, it downloads and stores the entire history of naturacoin transactions (which is currently several GBs); depending on the speed of your computer and network connection, the synchronization process can take anywhere from a few hours to a day or more. Thankfully you only have to do this once.

Running
---------------------
The following are some helpful notes on how to run naturacoin on your native platform. 

### Unix

You need the Qt4 run-time libraries to run naturacoin-Qt. On Debian or Ubuntu:

	sudo apt-get install libqtgui4

Unpack the files into a directory and run:

- bin/32/naturacoin-qt (GUI, 32-bit) or bin/32/naturacoind (headless, 32-bit)
- bin/64/naturacoin-qt (GUI, 64-bit) or bin/64/naturacoind (headless, 64-bit)



### Windows

Unpack the files into a directory, and then run naturacoin-qt.exe.

### OSX

Drag naturacoin-Qt to your applications folder, and then run naturacoin-Qt.

### Need Help?

* See the documentation at the [naturacoin Wiki](http://freshco.in/)
for help and more information.
* Ask for help on [#naturacoin](http://webchat.freenode.net?channels=naturacoin) on Freenode. If you don't have an IRC client use [webchat here](http://webchat.freenode.net?channels=naturacoin).
* Ask for help on the [/r/freshducation subreddit](http://reddit.com/r/freshducation).

Building
---------------------
The following are developer notes on how to build naturacoin on your native platform. They are not complete guides, but include notes on the necessary libraries, compile flags, etc.

- [OSX Build Notes](build-osx.md)
- [Unix Build Notes](build-unix.md)
- [Windows Build Notes](build-msw.md)

Development
---------------------
The naturacoin repo's [root README](https://github.com/naturacoin/naturacoin/blob/master/README.md) contains relevant information on the development process and automated testing.

- [Coding Guidelines](coding.md)
- [Multiwallet Qt Development](multiwallet-qt.md)
- [Release Notes](release-notes.md)
- [Release Process](release-process.md)
- [Source Code Documentation (External Link)](https://dev.visucore.com/bitcoin/doxygen/)
- [Translation Process](translation_process.md)
- [Unit Tests](unit-tests.md)

### Resources
* Discuss on the [/r/naturacoindev](http://www.reddit.com/r/naturacoindev) subreddit.
* Discuss on [#naturacoin-dev](http://webchat.freenode.net/?channels=naturacoin-dev) on Freenode. If you don't have an IRC client use [webchat here](http://webchat.freenode.net/?channels=naturacoin-dev).

### Miscellaneous
- [Assets Attribution](assets-attribution.md)
- [Files](files.md)
- [Tor Support](tor.md)

License
---------------------
Distributed under the [MIT/X11 software license](http://www.opensource.org/licenses/mit-license.php).
This product includes software developed by the OpenSSL Project for use in the [OpenSSL Toolkit](http://www.openssl.org/). This product includes
cryptographic software written by Eric Young ([eay@cryptsoft.com](mailto:eay@cryptsoft.com)), and UPnP software written by Thomas Bernard.
