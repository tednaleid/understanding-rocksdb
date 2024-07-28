# Understanding RocksDB

<p align="center">
  <img src="images/rocksdb_high_level.png" alt="RocksDB High Level">
</p>

I've used [RocksDB](https://rocksdb.org/) as an ephemeral datastore for event streaming platforms processing billions of requests a day, and as backing for high-scale http APIs that have served hundreds of thousands of requests per second.

This repo has a [slide deck](presentation.pdf) explaining the externals of RocksDB.  It also includes tuning suggestions that I've found useful.
