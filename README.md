Rothscoin integration/staging tree
================================

http://rothscoin.com

Copyright (c) 2009-2014 Bitcoin Developers
Copyright (c) 2017-2018 Rothscoin Developers

What is Rothscoin?
----------------

Rothscoin is a lite version of Bitcoin using scrypt as a proof-of-work algorithm.
 - ~89 million total coins
 - Premine 28 million coins
 - 2 minutes block targets
 - 10 coins per block
 - subsidy halves in 1314000 blocks (~5 years)
 - 720 blocks to retarget difficulty

For more information, as well as an immediately useable, binary version of
the Rothscoin client sofware, see http://rothscoin.com.

License
-------

Rothscoin is released under the terms of the MIT license. See `COPYING` for more
information or see http://opensource.org/licenses/MIT.

Development process
-------------------

Developers work in their own trees, then submit pull requests when they think
their feature or bug fix is ready.

If it is a simple/trivial/non-controversial change, then one of the Rothscoin
development team members simply pulls it.

If it is a *more complicated or potentially controversial* change, then the patch
submitter will be asked to start a discussion with the devs and community.

The patch will be accepted if there is broad consensus that it is a good thing.
Developers should expect to rework and resubmit patches if the code doesn't
match the project's coding conventions (see `doc/coding.txt`) or are
controversial.

The `master` branch is regularly built and tested, but is not guaranteed to be
completely stable. [Tags](https://github.com/rothscoin/rtccoin) are created
regularly to indicate new official, stable release versions of Rothscoin.

Testing
-------

Testing and code review is the bottleneck for development; we get more pull
requests than we can review and test. Please be patient and help out, and
remember this is a security-critical project where any mistake might cost people
lots of money.

### Automated Testing

Developers are strongly encouraged to write unit tests for new code, and to
submit new unit tests for old code.
