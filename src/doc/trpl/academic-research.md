% Academic Research

An incomplete list of papers that have had some influence in Rust.

Recommended for inspiration and a better understanding of Rust's background.

### Type system

* [Region based memory management in Cyclone](http://209.68.42.137/ucsd-pages/Courses/cse227.w03/handouts/cyclone-regions.pdf)
* [Safe manual memory management in Cyclone](http://www.cs.umd.edu/projects/PL/cyclone/scp.pdf)
* [Typeclasses: making ad-hoc polymorphism less ad hoc](http://www.ps.uni-sb.de/courses/typen-ws99/class.ps.gz)
* [Macros that work together](https://www.cs.utah.edu/plt/publications/jfp12-draft-fcdf.pdf)
* [Traits: composable units of behavior](http://scg.unibe.ch/archive/papers/Scha03aTraits.pdf)
* [Alias burying](http://www.cs.uwm.edu/faculty/boyland/papers/unique-preprint.ps) - We tried something similar and abandoned it.
* [External uniqueness is unique enough](http://www.computingscience.nl/research/techreps/repo/CS-2002/2002-048.pdf)
* [Uniqueness and Reference Immutability for Safe Parallelism](https://research.microsoft.com/pubs/170528/msr-tr-2012-79.pdf)
* [Region Based Memory Management](http://www.cs.ucla.edu/~palsberg/tba/papers/tofte-talpin-iandc97.pdf)

### Concurrency

* [Singularity: rethinking the software stack](https://research.microsoft.com/pubs/69431/osr2007_rethinkingsoftwarestack.pdf)
* [Language support for fast and reliable message passing in singularity OS](https://research.microsoft.com/pubs/67482/singsharp.pdf)
* [Scheduling multithreaded computations by work stealing](http://supertech.csail.mit.edu/papers/steal.pdf)
* [Thread scheduling for multiprogramming multiprocessors](http://www.eecis.udel.edu/%7Ecavazos/cisc879-spring2008/papers/arora98thread.pdf)
* [The data locality of work stealing](http://www.aladdin.cs.cmu.edu/papers/pdfs/y2000/locality_spaa00.pdf)
* [Dynamic circular work stealing deque](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.170.1097&rep=rep1&type=pdf) - The Chase/Lev deque
* [Work-first and help-first scheduling policies for async-finish task parallelism](http://www.cs.rice.edu/%7Eyguo/pubs/PID824943.pdf) - More general than fully-strict work stealing
* [A Java fork/join calamity](http://www.coopsoft.com/ar/CalamityArticle.html) - critique of Java's fork/join library, particularly its application of work stealing to non-strict computation
* [Scheduling techniques for concurrent systems](http://www.ece.rutgers.edu/%7Eparashar/Classes/ece572-papers/05/ps-ousterhout.pdf)
* [Contention aware scheduling](http://www.blagodurov.net/files/a8-blagodurov.pdf)
* [Balanced work stealing for time-sharing multicores](http://www.cse.ohio-state.edu/hpcs/WWW/HTML/publications/papers/TR-12-1.pdf)
* [Three layer cake](http://www.upcrc.illinois.edu/workshops/paraplop10/papers/paraplop10_submission_8.pdf)
* [Non-blocking steal-half work queues](http://www.cs.bgu.ac.il/%7Ehendlerd/papers/p280-hendler.pdf)
* [Reagents: expressing and composing fine-grained concurrency](http://www.mpi-sws.org/~turon/reagents.pdf)
* [Algorithms for scalable synchronization of shared-memory multiprocessors](https://www.cs.rochester.edu/u/scott/papers/1991_TOCS_synch.pdf)

### Others

* [Crash-only software](https://www.usenix.org/legacy/events/hotos03/tech/full_papers/candea/candea.pdf)
* [Composing High-Performance Memory Allocators](http://people.cs.umass.edu/~emery/pubs/berger-pldi2001.pdf)
* [Reconsidering Custom Memory Allocation](http://people.cs.umass.edu/~emery/pubs/berger-oopsla2002.pdf)

### Papers *about* Rust

* [GPU programming in Rust](http://www.cs.indiana.edu/~eholk/papers/hips2013.pdf)
* [Parallel closures: a new twist on an old idea](https://www.usenix.org/conference/hotpar12/parallel-closures-new-twist-old-idea) - not exactly about rust, but by nmatsakis
