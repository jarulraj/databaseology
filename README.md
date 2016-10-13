# Database Systems Reading List

These papers should help the reader better appreciate the design and implementation of modern database management systems (DBMSs). By design, this reading list only contains papers that were published atleast 10 years ago. If you would like to add a paper to this reading list, submit a [pull request](https://github.com/jarulraj/databaseology/blob/master/CONTRIBUTING.md).

- [Case Studies](#case-studies)
- [Access Methods](#access-methods)
- [Query Optimization](#query-optimization)
- [Query Processing](#query-processing)
- [Concurrency Control](#concurrency-control)
- [Recovery](#recovery)
- [Data Models](#data-models)
- [Distributed Data Processing](#distributed-data-processing)
- [Parallel Data Processing](#parallel-data-processing)
- [Operating System Issues](#operating-system-issues)
- [Data Storage](#data-storage)
- [Main Memory DBMSs](#main-memory-dbmss)
- [Optimizing for Hardware](#optimizing-for-hardware)
- [Self-Tuning DBMSs](#self-tuning-dbmss)
- [Triggers and Streams](#triggers-and-streams)

- - -

## Case Studies

* [A History and Evaluation of System R](http://www.cs.berkeley.edu/~brewer/cs262/SystemR.pdf)
* [A Relational Model of Data for Large Shared Data Banks](https://www.seas.upenn.edu/~zives/03f/cis550/codd.pdf)
* [The Design of the POSTGRES Storage System](http://db.cs.berkeley.edu/papers/ERL-M87-06.pdf)
* [Architecture of a Database System](http://db.cs.berkeley.edu/papers/fntdb07-architecture.pdf)

## Access Methods

 * [The Ubiquitous B-Tree](https://wwwold.cs.umd.edu/class/fall2002/cmsc818s/Readings/b-tree.pdf)
 * [R-Trees: A Dynamic Index Structure for Spatial Searching](http://pages.cs.wisc.edu/~cs764-1/rtree.pdf)
 * [Improved Query Performance with Variant Indexes](https://www.cs.duke.edu/courses/spring03/cps216/papers/oneil-quass-1997.pdf)

## Query Optimization

 * [Access Path Selection in a Relational Database Management System](http://www.cs.columbia.edu/~coms4111/docs/selinger.pdf)
 * [An Overview of Query Optimization in Relational Systems](http://research.microsoft.com/pubs/76059/pods98-tutorial.pdf)
 * [R* Optimizer Validation and Performance Evaluation for Distributed Queries](https://www.cs.utexas.edu/users/dsb/cs386d/Readings/QueryProcessing/R-Star.PDF)

## Query Processing

 * [Query Evaluation Techniques for Large Databases](http://bnrg.cs.berkeley.edu/~adj/cs262/papers/graefe.pdf)
 * [Join Processing in Database Systems with Large Main Memories](http://daslab.seas.harvard.edu/reading-group/papers/join.pdf)
 * [Data Cube : A Relational Aggregation Operator Generalizing Group By, Cross Tab, and Sub Totals](http://research.microsoft.com/pubs/69578/tr-95-22.pdf)
 * [An Overview of Data Warehousing and OLAP Technology](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/02/sigrecord.pdf)

## Concurrency Control

 * [Efficient Locking for Concurrent Operations on B-Trees](http://www.csd.uoc.gr/~hy460/pdf/p650-lehman.pdf)
 * [On Optimistic Methods for Concurrency Control](http://daslab.seas.harvard.edu/reading-group/papers/kung.pdf)
 * [Granularity of Locks and Degrees of Consistency in a Shared Data Base](http://research.microsoft.com/en-us/um/people/gray/papers/Granularity%20of%20Locks%20and%20Degrees%20of%20Consistency%20RJ%201654.pdf)
 * [A Critique of ANSI SQL Isolation Levels](http://research.microsoft.com/pubs/69541/tr-95-51.pdf)

## Recovery

 * [ARIES: A Transaction Recovery Method Supporting Fine Granularity Locking and Partial Rollbacks Using Write Ahead Logging](https://www.cs.berkeley.edu/~brewer/cs262/Aries.pdf)
 * [Why Do Computers Stop And What Can Be Done About It ?](http://www.hpl.hp.com/techreports/tandem/TR-85.7.pdf)

## Data Models

 * [What Goes Around Comes Around](https://mitpress.mit.edu/sites/default/files/titles/content/9780262693141_sch_0001.pdf)

## Distributed Data Processing

 * [Transaction Management in the R* Distributed Database Management System](http://www.cs.cmu.edu/~natassa/courses/15-823/F02/papers/p378-mohan.pdf)
 * [A Case for Fractured Mirrors](http://www.vldb.org/conf/2002/S12P03.pdf)
 * [Consensus on Transaction Commit](http://research.microsoft.com/pubs/64636/tr-2003-96.pdf)
 * [Mariposa: A Wide-Area Distributed Database System](http://pages.cs.wisc.edu/~cs764-1/mariposa.pdf)

## Parallel Data Processing

 * [Parallel Database Systems: The Future of High Performance Database Systems](https://www.cs.berkeley.edu/~brewer/cs262/5-dewittgray92.pdf)
 * [Encapsulation of Parallelism in the Volcano Query Processing System](http://daslab.seas.harvard.edu/reading-group/papers/encapsulation-volcano.pdf)
 * [The GAMMA Database Machine Project](http://pages.cs.wisc.edu/~dewitt/includes/paralleldb/ieee90.pdf)

## Operating System Issues

 * [Operating System Support for Database Management](http://www.cs.berkeley.edu/~prabal/resources/osprelim/Sto81.pdf)
 * [An Evaluation of Buffer Management Strategies for Relational Database Systems](http://www.csd.uoc.gr/~hy460/pdf/DBBufMgmt.pdf)

## Data Storage

 * [Data Morphing: An Adaptive, Cache-Conscious Storage Technique](http://citeseerx.ist.psu.edu/viewdoc/summary?doi=10.1.1.9.8223)
 * [A Case for Redundant Arrays of Inexpensive Disks](http://www.cs.cmu.edu/~garth/RAIDpaper/Patterson88.pdf)

## Main Memory DBMSs

 * [Main Memory Database Systems: An Overview](http://pages.cs.wisc.edu/~jhuang/qual/main-memory-db-overview.pdf)

## Optimizing for Hardware

 * [DBMSs on a Modern Processor: Where Does Time Go?](http://www.vldb.org/conf/1999/P28.pdf)
 * [Database Architecture Optimized for the New Bottleneck: Memory Access](http://www.vldb.org/conf/1999/P5.pdf)

## Self-Tuning DBMSs

 * [Rethinking Database System Architecture: Towards a Self-Tuning RISC-Style Database System](http://www.vldb.org/conf/2000/P001.pdf)

## Triggers and Streams

 * [Data Stream Management Issues: A Survey](http://www.sigmod.org/record/issues/0306/1.golab-ozsu1.pdf)
 * [Scalable Trigger Processing](https://dl.acm.org/citation.cfm?id=847241)
