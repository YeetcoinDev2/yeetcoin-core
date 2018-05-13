Yeetcoin Core integration/staging tree
=====================================

[![Build Status](https://travis-ci.org/litecoin-project/litecoin.svg?branch=master)](https://travis-ci.org/litecoin-project/litecoin)

https://yeetco.in

What is Yeetcoin?
----------------

Yeetcoin is a digital currency based off Litecoin and the original Bitcoin Whitepaper that
enables encrypted payments anywhere in the world. Yeetcoin uses peer-to-peer technology to
operate; using networked computers to carry out transactions and deliver them securely.
Yeetcoin Core is the name of an open source wallet which enables the use of this currency.

For more information about Yeetcoin as well as the executable forms of the software,
visit our website [https://Yeetco.in](https://yeetco.in).

License
-------

Yeetcoin Core is released under the terms of the MIT license. See [COPYING](COPYING) for more
information or see https://opensource.org/licenses/MIT.

Development Process
-------------------

Yeetcoin is currently in early alpha, and will be updated very frequently. None of these
releases are to be considered stable.

### Automated Testing

Developers are strongly encouraged to write [unit tests](src/test/README.md) for new code, and to
submit new unit tests for old code. Unit tests can be compiled and run
(assuming they weren't disabled in configure) with: `make check`. Further details on running
and extending unit tests can be found in [/src/test/README.md](/src/test/README.md).

There are also [regression and integration tests](/test), written
in Python, that are run automatically on the build server.
These tests can be run (if the [test dependencies](/test) are installed) with: `test/functional/test_runner.py`

The Travis CI system makes sure that every pull request is built for Windows, Linux, and OS X, and that unit/sanity tests are run automatically.

### Manual Quality Assurance (QA) Testing

Changes should be tested by somebody other than the developer who wrote the
code. This is especially important for large or high-risk changes. It is useful
to add a test plan to the pull request description if testing the changes is
not straightforward.
