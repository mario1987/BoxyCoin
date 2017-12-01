### Installing Ubuntu Node

##  Secure your node from outside world
    ufw allow ssh
    ufw allow 21524
    ufw allow 21523
    ufw default deny incoming
    ufw default allow outgoing
    ufw enable

    sudo apt-get install ntp git build-essential libssl-dev libdb-dev libdb++-dev libboost-all-dev libqrencode-dev libcurl4-openssl-dev     sudo apt-get install curl libzip-dev libzip2
    sudo apt-get install libboost-all-dev
    sudo apt-get install build-essential libtool autotools-dev autoconf pkg-config libssl-dev
    sudo apt-get upgrade
    sudo apt-get install libminiupnpc-dev 
    sudo apt-get install libdb4.8-dev
    sudo apt-get install libdb++-dev
    sudo apt-get install libdb4.8++-dev
    sudo apt-get install libboost1.37-dev
    sudo apt-get update
    
 ## (If using Boost 1.37, append -mt to the boost libraries in the makefile)
    
    git clone http://www.github.com/boxycoin/boxycoin.git
    cd /boxycoin/src 
    sed -i 's/<const\ CScriptID\&/<CScriptID/' rpcrawtransaction.cpp
    make -f makefile.unix USE_UPNP=-

    ./boxycoind 
## (set username and password in boxy.conf under hidden folder .boxy)
    cd .boxy

## Using your node -- Mining stats, listing accounts and balances, generate new addresses, mining
    ./boxycoind getmininginfo 
    ./boxycoind listaccounts
    ./boxycoind listreceivedbyaddress 0 true
    ./boxycoind getnew address
    ./boxycoind setgenerate true
