QFS
===

Welcome to QFS!

Quantcast File System (QFS) is a high-performance, fault-tolerant, distributed file system developed to support applications with sequential access pattern over large files.


Compiling And Running
---------------------

The [QFS Wiki](https://github.com/quantcast/qfs/wiki) has details on compiling QFS and running it.

The pre-requisite packages for the build system are discussed **[here](https://github.com/quantcast/qfs/wiki/Developer-Documentation)**.

 For a quick start, one could run the following commands from the top-level directory:
* Build Code:
  Ensure boost and cmake are installed / available.
  `make`
* Try Out:
  `make` and `examples/sampleservers/sample_setup.py --help`
* Benchmark:
  `make`, `cd benchmarks/mstress` and `./mstress_sample_run.sh`

Quick Links
-----------

* [Getting Started](http://github.com/quantcast/qfs/wiki)
* [Repository Organization](https://github.com/quantcast/qfs/wiki/Repository-Organization)
* [Developer Documentation](https://github.com/quantcast/qfs/wiki/Developer-Documentation)
* [Benchmarking](https://github.com/quantcast/qfs/wiki/Benchmarking)

Contributing to QFS
===================

QFS is an open source, community-driven project, and we would like you to contribute. Please read the [Code Contribution Policy]() page for further information.

License
=======

QFS is released under the Apache 2.0 license. A copy of the license is included in the file [LICENSE.txt](https://github.com/quantcast/qfs/blob/master/LICENSE.txt).
