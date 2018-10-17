Zcash 2.0.0
=============

## ondrejsika/regtest

This branch contains some differences between zcash/master for regtest chain

- __equihash params__ - production equihash params 200, 9
- __halving__ - standart halving after 840 000 blocks
- __coinbase output protection__ - coinbase outputs can be sent only to zaddr as on livenet


What is Zcash?
--------------

[Zcash](https://z.cash/) is an implementation of the "Zerocash" protocol.
Based on Bitcoin's code, it intends to offer a far higher standard of privacy
through a sophisticated zero-knowledge proving scheme that preserves
confidentiality of transaction metadata. Technical details are available
in our [Protocol Specification](https://github.com/zcash/zips/raw/master/protocol/protocol.pdf).

This software is the Zcash client. It downloads and stores the entire history
of Zcash transactions; depending on the speed of your computer and network
connection, the synchronization process could take a day or more once the
blockchain has reached a significant size.

Security Warnings
-----------------

See important security warnings on the
[Security Information page](https://z.cash/support/security/).

**Zcash is experimental and a work-in-progress.** Use at your own risk.

Deprecation Policy
------------------

This release is considered deprecated 16 weeks after the release day. There
is an automatic deprecation shutdown feature which will halt the node some
time after this 16 week time period. The automatic feature is based on block
height and can be explicitly disabled.

Where do I begin?
-----------------
We have a guide for joining the main Zcash network:
https://github.com/zcash/zcash/wiki/1.0-User-Guide

### Need Help?

* See the documentation at the [Zcash Wiki](https://github.com/zcash/zcash/wiki)
  for help and more information.
* Ask for help on the [Zcash](https://forum.z.cash/) forum.

Participation in the Zcash project is subject to a
[Code of Conduct](code_of_conduct.md).

Building
--------

Build Zcash along with most dependencies from source by running
``./zcutil/build.sh -j$(nproc) ``. Currently only Linux is officially supported.

License
-------

For license information see the file [COPYING](COPYING).
