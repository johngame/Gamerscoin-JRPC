Gamerscoin-JRPC
=============

A java api that wraps the gamerscoind JSON-RPC api.  [![tip for next commit](http://game4commit.gamers-coin.org/projects/24.svg)](http://game4commit.gamers-coin.org/projects/24)

[What's gamerscoin?](http://gamers-coin.org/)


![Gamerscoin](https://raw.githubusercontent.com/gamers-coin/gamers-coinv3/01d1ca6d63b565ea46dcee3b6552b030d57d1187/src/qt/res/icons/bitcoin.png)![Gamerscoin](http://i.imgur.com/Nfb8DQx.png)

### Requirements:

`gamerscoind` [for linux](https://github.com/gamers-coin/gamers-coinv3)
`gamerscoind` [for Win](http://gamers-coin.org/downloads)
`gamerscoind` [for Mac](http://gamers-coin.org/downloads)

### Maven:

    <dependency>
	    <groupId>com.github.johngame</groupId>
	    <artifactId>gamerscoin-jrpc</artifactId>
	    <version>0.1</version>
    </dependency>

### Build the api:

    git clone https://github.com/johngame/Gamerscoin-JRPC
    cd Gamerscoin-JRPC/
    mvn clean install
    
### Configuration:

Set environment variables used to access the `gamerscoind` instance:

    export GAMERS_COIN_RPC_USERNAME=YOUR_USER
    export GAMERS_COIN_RPC_PASSWORD=YOUR_PASSWORD

### Test:

    cd Gamersoin-JRPC/
    mvn clean test
    
### Improvements:

All contributors are welcome!
