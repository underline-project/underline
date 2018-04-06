Underline Core integration/staging tree
=====================================

[![Build Status](https://travis-ci.org/underline-project/underline.svg?branch=master)](https://travis-ci.org/underline-project/underline)

https://underline.org

What is Underline?
----------------

Underline is an experimental digital currency fork from [LITECOIN](https://github.com/litecoin-project/litecoin) 
that enables instant payments to anyone, anywhere in the world. 

Underline contains a number of significant performance improvements, which make
Initial Block Download, startup, transaction and block validation much faster;
As a result, validating the blockchain during Initial Block Download (IBD) and reindex
is ~30-40% faster, uses 10-20% less memory, and flushes to disk far less frequently.
The only downside is that the on-disk database is 15% larger. During the conversion from the previous format
a few extra gigabytes may be used.

Underline Core is the name of open source software which enables the use of this currency.

For more information, as well as an immediately useable, binary version of
the Underline Core software, see [https://underline.org](https://underline.org).

License
-------

Underline Core is released under the terms of the MIT license. See [COPYING](COPYING) for more
information or see https://opensource.org/licenses/MIT.

Development Process
-------------------

The `master` branch is regularly built and tested, but is not guaranteed to be
completely stable. [Tags](https://github.com/underline-project/underline/tags) are created
regularly to indicate new official, stable release versions of Underline Core.

The contribution workflow is described in [CONTRIBUTING.md](CONTRIBUTING.md).

The developer [mailing list](https://groups.google.com/forum/#!forum/underline-dev)
should be used to discuss complicated or controversial changes before working
on a patch set.

Developer IRC can be found on Freenode at #underline-dev.

**Important**: We do not accept translation changes as GitHub pull requests because the next
pull from Transifex would automatically overwrite them again.
