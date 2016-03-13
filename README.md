TraderCoin integration/staging tree
================================



Copyright (c) 2009-2014 Bitcoin Developers
Copyright (c) 2016 TraderCoin Developers

#### DISCLAIMER ####

Hello guys, we are not coins developers, we are traders that operate markets as Forex, Bitcoin and altcoins.

Our goal is to study about cryptocurrency and have another point of view within the altcoins market, we have some points that will be presented on 20 May, one of the points we call Progressive Buy Wall.

Our team consists of traders and bought the service walletbuilders.com to create a coin for us, we always had a desire to learn more about the development of cryptocurrency and decided to do it.

The basis of our project is for fun, we release the source code of our project to be checked, because we can not guarantee that the files are reliable, although Walletbuilders.com affirm that yes, use at your own risk.

All of the executable on the site virustotal.com and use at your own risk.

We suggest using the currency in test environments and for study purposes, but later could we put tradercoin in exchanges


#### What is Tradercoin ? #####

Tradercoin is a currency originally created to serve as a form of payment for our reports , courses, coach , events, tips on bitcoin and altcoins , and our services available both offline and online.
We are studying the market , we want to learn about the behavior of cryptocurrency and we have the support of the community

#### Advantages of Tradercoin? ####

Initially , given the purpose of the coin studies , we will ensure an appreciation of Tradercoin , and the symbolic starting price of 1 satoshi , and can later rise to 2 satoshis or more , always previously communicating to our community .
Those who buy our products using Tradercoin will have a 50% discount , we will soon have a list of products and services.

#### As the Tradercoin will be distributed? ####

The tradercoin will be distributed using mining CPU , so everyone can have access to tradercoin some tradercoins are with our team and will be used as awards to the creators for the first year of service as well as to pay third-party services that are not linked to project.


######  PROJECT  #####

As we said before , we do not have experience in developing cryptocurrency and we are using the Tradercoin as a test , therefore , we remember the risk of the use of files and remember that if they wish can check the code in the available site .

1) Until 15 April we will be focused on monitoring the mining and know how its development ;

2 ) Until May 20 we will launch a website for Tradercoin ;

3 ) Until May 20 we will have the release of the progressive Buywall system;

4 ) On May 27, we will make the announcement of the second stage of Tradercoin .


License
-------

TraderCoin is released under the terms of the MIT license. See `COPYING` for more
information or see http://opensource.org/licenses/MIT.

Development process
-------------------

Developers work in their own trees, then submit pull requests when they think
their feature or bug fix is ready.

If it is a simple/trivial/non-controversial change, then one of the TraderCoin
development team members simply pulls it.

If it is a *more complicated or potentially controversial* change, then the patch
submitter will be asked to start a discussion with the devs and community.

The patch will be accepted if there is broad consensus that it is a good thing.
Developers should expect to rework and resubmit patches if the code doesn't
match the project's coding conventions (see `doc/coding.txt`) or are
controversial.

The `master` branch is regularly built and tested, but is not guaranteed to be
completely stable. [Tags](https://github.com/tradercoin-project/tradercoin/tags) are created
regularly to indicate new official, stable release versions of TraderCoin.

Testing
-------

Testing and code review is the bottleneck for development; we get more pull
requests than we can review and test. Please be patient and help out, and
remember this is a security-critical project where any mistake might cost people
lots of money.

### Automated Testing

Developers are strongly encouraged to write unit tests for new code, and to
submit new unit tests for old code.

Unit tests for the core code are in `src/test/`. To compile and run them:

    cd src; make -f makefile.unix test

Unit tests for the GUI code are in `src/qt/test/`. To compile and run them:

    qmake BITCOIN_QT_TEST=1 -o Makefile.test bitcoin-qt.pro
    make -f Makefile.test
    ./tradercoin-qt_test

