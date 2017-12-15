BoxyCoin Readme First
================================

http://www.boxycoin.org

http://www.boxy.online

Copyright (c) 2009-2014 Bitcoin Developers

Copyright (c) 2014-2017 Boxy Developers

What is Boxy?
----------------
Boxy is an open-source, peer-to-peer Internet currency forked from Bitcoin and inspired by Litecoin.
Like Bitcoin, it enables instant, near-zero cost payments to anyone in the world. 
Boxycoin's decentralised network is secured by complex mathematical computations which allows individuals to control 
their own finances. Compared to Bitcoin and Litecoin, Boxy features faster transaction confirmation times, 
improved security and ARTAX storage integration (the first of its kind). ARTAX technology is set to revolutionize 
blockchain storage worldwide due to the availability of encryption cache persistance (ECP).


Boxy is a lite version of Bitcoin using scrypt as a proof-of-work algorithm.
 - 65 second block targets
 - subsidy halves in 900k blocks 
 - 100 million total coins
 - no official pools before block 1000 (CPU mining only)
 - 30 coins per block
 - ARTAX blockchain integration
 - 2018 blocks to retarget difficulty

For more information, as well as an immediately useable, binary version of
the Boxy client sofware, see http://www.boxycoin.org

What is different about Boxycoin?

The coin code is not at all the difficult part of an endeavour like this. The difference quite simply is ARTAX. All crypto including BTC
to date have scaling issues, issues with blockchain sizes, tx sizes and security. ARTAX looks to take a flamethrower to all of these 
items by way of encryption cache persistence. We look to use Boxy as the first example of scaling nodes through one variable spectrum
and streamlining one de-centralised storage interface for the coins backend. The eventual intention is to have other people forking boxy
and ARTAX into newer, greater things and improvising the new ARTAX storage resolution into the cryptography landscape.

 
Source Code: http://www.github.com/boxycoin/boxycoin.git
Discord: https://discord.gg/6DSvyNV
Bitcoin talk thread: https://bitcointalk.org/index.php?topic=2401866.0
Facebook: http://www.facebook.com/Boxycoin
Website: http://www.boxycoin.org
Reddit: http://www.reddit.com/r/Boxycoin
 

License
-------

Boxy is released under the terms of the MIT license. See `COPYING` for more
information or see http://opensource.org/licenses/MIT.

Development process
-------------------

Developers work in their own trees, then submit pull requests when they think
their feature or bug fix is ready.

If it is a simple/trivial/non-controversial change, then one of the Boxy
development team members simply pulls it.

If it is a *more complicated or potentially controversial* change, then the patch
submitter will be asked to start a discussion with the devs and community.

The patch will be accepted if there is broad consensus that it is a good thing.
Developers should expect to rework and resubmit patches if the code doesn't
match the project's coding conventions (see `doc/coding.txt`) or are
controversial.

The `master` branch is regularly built and tested, but is not guaranteed to be
completely stable. [Tags](https://github.com/boxy-project/boxy/tags) are created
regularly to indicate new official, stable release versions of Boxy.

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



