Awesome system benchmark tools
===============================

CPU
---

- `Geekbench <https://www.geekbench.com/>`_ :
  Cross-platform benchmark that measures your system's performance with the press of a button.
- `sysbench (cpu) <https://github.com/akopytov/sysbench>`_ : 
  Scriptable multi-threaded benchmark tool based on LuaJIT.
- `openssl speed <https://www.openssl.org/docs/manmaster/man1/speed.html>`_:
  Cryptography performance measurement
- `V-Ray Benchmark <https://www.chaosgroup.com/vray/benchmark>`_:
  Free standalone application to test how fast your system renders.
- `Phoronix Test Suite <https://www.phoronix-test-suite.com/>`_:
  Testing and benchmarking platform available for Linux, Solaris, macOS, Windows, and BSD operating systems.
- `SPEC CPU <https://www.spec.org/cpu2017/>`_:
  SPEC's next-generation, industry-standardized, CPU intensive suites for measuring and comparing compute intensive performance, stressing a system's processor, memory subsystem and compiler.
- `VASP <https://www.hpc.cineca.it/content/vasp-benchmark>`_:
  The Vienna Ab initio Simulation Package is a computer program for atomic scale materials modelling, e.g. electronic structure calculations and quantum-mechanical molecular dynamics, from first principles.  
- `FinanceBench <http://cavazos-lab.github.io/FinanceBench/>`_:
  FinanceBench is aimed at those who work with financial code to see how certain code paths can be targeted for accelerators.
- `LAMMPS Benchmarks <https://lammps.org/bench.html>`_: Simple suite with Large-scale Atomic/Molecular Massively Parallel Simulator workloads
- `AI-Benchmark <https://ai-benchmark.com/>`_: Deep learning workloads
- `CoreMark <https://github.com/eembc/coremark>`_: Methods for testing only a processor's core features
- `CoreMark®-PRO <https://github.com/eembc/coremark-pro>`_: Comprehensive, advanced processor benchmark that works with and enhances the market-proven industry-standard EEMBC CoreMark®
- `db-benchmark <https://github.com/h2oai/db-benchmark>`_: Reproducible benchmarking of database-like operations in single-node environment.
- `Renaissance Benchmark Suite <https://github.com/renaissance-benchmarks/renaissance>`_: Aggregates common modern JVM workloads, including, but not limited to, Big Data, machine-learning, and functional programming.
- `The Computer Language Benchmarks Game <https://salsa.debian.org/benchmarksgame-team/benchmarksgame>`_: Toy-program performance measurements for ~24 language implementations.
- `pyhpc-benchmark <https://github.com/dionhaefner/pyhpc-benchmarks>`_: Suite of benchmarks to test the sequential CPU and GPU performance of various computational backends with Python frontends

RAM
---
- `STREAM <http://www.cs.virginia.edu/stream/>`_:
- `sysbench (memory) <https://github.com/akopytov/sysbench>`_ : 
  Scriptable multi-threaded benchmark tool based on LuaJIT.


Storage
-------
- `Flexible I/O Tester (FIO) <https://fio.readthedocs.io/en/latest/fio_doc.html>`_:
  Spawns a number of threads or processes doing a particular type of I/O action as specified by the user.
- `vdbench <https://sourceforge.net/projects/vdbench/>`_:
  Disk and tape I/O workload generator for verifying data integrity and measuring performance of storage.
- `iozone <http://iozone.org/>`_:
  Filesystem benchmark tool
- `hdparam <https://linux.die.net/man/8/hdparm>`_:
  Command line interface to various kernel interfaces.
- `oiping <https://github.com/koct9i/ioping>`_ Shows disk latency in the same way as ping shows network latency.

Network
-------
- `iperf <https://iperf.fr/>`_:
  Active measurements of the maximum achievable bandwidth on IP networks.
- `tracepath <https://linux.die.net/man/8/tracepath>`_:
  Trace path to destination discovering MTU along this path.
- `traceroute <https://linux.die.net/man/8/traceroute>`_:
  racks the route packets taken from an IP network on their way to a given host.
- `tcptraceroute <https://linux.die.net/man/1/tcptraceroute>`_:
  traceroute implementation using TCP packets.
- `paris-traceroute <https://paris-traceroute.net/index.html>`_: Paris traceroute is a new version of the well-known network diagnosis and measurement tool. It addresses problems caused by load balancers with the initial implementation of traceroute. 
- `dublin-traceroute <https://github.com/insomniacslk/dublin-traceroute>`_: Dublin Traceroute is a NAT-aware multipath traceroute tool.
- `mtr <https://github.com/traviscross/mtr>`_: Combines the functionality of the 'traceroute' and 'ping' programs in a single network diagnostic tool.

HTTP
----
- `ab (apache benchmark) <http://httpd.apache.org/docs/2.4/programs/ab.html>`_:
  Load testing and benchmarking tool for HTTP servers.
- `cURL <https://curl.se/>`_:
  Command line tool and library for transferring data with URLs.
- `wrk <https://github.com/wg/wrk>`_:
  Modern HTTP benchmarking tool capable of generating significant load when run on a single multi-core CPU.
- `os-benchmark <https://github.com/cloudmercato/os-benchmark>`_ : Simple tool to collect metrics about all object storage.
- `s3-benchmark <https://github.com/dvassallo/s3-benchmark>`_: Measure S3's performance from any location
- `warp <https://github.com/awesome-benchmark/warp>`_: S3 benchmarking tool 

Database and messaging
----------------------
- `redis-benchmark <https://redis.io/topics/benchmarks>`_:
  Utility that simulates running commands done by N clients at the same time sending M total querie 
- `memtier_benchmark <https://github.com/RedisLabs/memtier_benchmark>`_:
  Command line utility developed for load generation and bechmarking NoSQL key-value databases.
- `sysbench (oltp) <https://github.com/akopytov/sysbench>`_ : 
  Scriptable multi-threaded benchmark tool based on LuaJIT.
- `sysbench TPCC <https://github.com/Percona-Lab/sysbench-tpcc>`_: 
  TPCC-like workload for sysbench 1.0.x.
- `YCSB <https://github.com/brianfrankcooper/YCSB>`_:
  Framework and common set of workloads for evaluating the performance of different “key-value” and “cloud” serving stores
- `benchyou <https://github.com/xelabs/benchyou>`_:
  benchyou is a benchmark tool for MySQL, similar to Sysbench.
- `Cassandra Stress <https://cassandra.apache.org/doc/latest/cassandra/tools/cassandra_stress.html>`_:
  Benchmark and load-test a Cassandra cluster
- `HammerDB <https://www.hammerdb.com/index.html>`_:
  Benchmarking and load testing software for the worlds most popular databases supporting Oracle Database, SQL Server, IBM Db2, MySQL, MariaDB and PostgreSQL.
- `mysqlslap <https://dev.mysql.com/doc/refman/8.0/en/mysqlslap.html>`_: Emulate client load for a MySQL server and to report the timing of each stage.
- `pgbench <https://www.postgresql.org/docs/current/pgbench.html>`_: It runs the same sequence of SQL commands over and over and then calculates the average transaction rate.
- `OpenMessaging Benchmark Framework <https://github.com/openmessaging/benchmark>`_: Suite of tools that make it easy to benchmark distributed messaging systems in the cloud.
- `opensearch-benchmark <https://github.com/opensearch-project/OpenSearch-Benchmark>`_: Macrobenchmarking framework for OpenSearch
- `Rally <https://github.com/elastic/rally>`_: Macrobenchmarking framework for Elasticsearch


  
GPU
---
- `AI-Benchmark <https://ai-benchmark.com/>`_
- `lambda-tensorflow-benchmark <https://github.com/lambdal/lambda-tensorflow-benchmark>`_
- `PyTorch Benchmarks <https://github.com/lambdal/deeplearning-benchmark/tree/master/pytorch>`_
- `V-Ray Benchmark <https://www.chaosgroup.com/vray/benchmark>`_:
- `Mixbench <https://github.com/ekondis/mixbench>`_:
  Evaluate performance bounds of GPUs on mixed operational intensity kernels.
- `gpu-burn <https://github.com/wilicc/gpu-burn>`_:
  Multi-GPU CUDA stress test.

Big data
--------
- `HiBench <https://github.com/Intel-bigdata/HiBench>`_:
  The bigdata micro benchmark suite.
- `YCSB <https://github.com/brianfrankcooper/YCSB>`_:
  Framework and common set of workloads for evaluating the performance of different “key-value” and “cloud” serving stores.
  
Scheduler
---------

- `Open Charge Tester (OCT) <https://github.com/TheGhouls/oct>`_:
  The tools to load testing just anything at any scale.
- `Apache JMeter <https://jmeter.apache.org/index.html>`_:
  Load test functional behavior and measure performance.
  
Ecology and environment
-----------------------

- `Eco benchmark <https://github.com/Boavizta/ecobenchmark-applicationweb-backend>`_:
  Try to compare the energy consumption, for several languages.
- `Scaphandre <https://github.com/hubblo-org/scaphandre>`_:
  Metrology agent dedicated to electrical power consumption metrics.
  
Comment
-------

Do not forget that any task/workload can be a benchmark, it always depends of your goal.
