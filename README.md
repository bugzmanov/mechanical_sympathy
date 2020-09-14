<p align="center">
  <img src="https://user-images.githubusercontent.com/502482/92668997-502cdb80-f2de-11ea-8f30-f38b9849d8d8.png" alt="Love thy hardware" width="40%">
</p>

# Curated list of resources about hardware for software developers

> The term Mechanical Sympathy was coined by racing driver Jackie Stewart and applied to software by Martin Thompson. Jackie Stewart said, “You don’t have to be an engineer to be be a racing driver, but you do have to have Mechanical Sympathy.” He meant that understanding how a car works makes you a better driver. This is just as true for writing code. You do need to understand how the hardware works and take that into consideration when you design software. 
>
>(from [here](https://dzone.com/articles/mechanical-sympathy))

## Fundamentals

* [Book: The Elements of Computing Systems: Building a Modern Computer from First Principles](https://www.amazon.com/Elements-Computing-Systems-Building-Principles/dp/0262640686) - how to build modern computer with a boolean logic gate, step by step.
* [Book: Systems Performance: Enterprise and the Cloud](https://www.amazon.com/Systems-Performance-Enterprise-Brendan-Gregg/dp/0133390098) - not really fundamentals, but covers most of hardware aspects, starting from concepts and ending with performance tunning for every hardware type.
* [Book: Computer Architecture: A Quantitative Approach](https://www.amazon.com/Computer-Architecture-Quantitative-John-Hennessy/dp/012383872X)

#### Videos

* [From NAND gates to tetris](https://www.coursera.org/learn/build-a-computer) - a course based on the "elements of computer systems" book
* [Cliff Click - A Crash Course in Modern Hardware](https://www.youtube.com/watch?v=5ZOuCuGrw48)

## RAM 

* [Paper: What every programmer should know about memory](https://akkadia.org/drepper/cpumemory.pdf) (+ [what has changed](https://stackoverflow.com/questions/8126311/what-every-programmer-should-know-about-memory) ) - covers everything there is to know for software people. After reading this paper [DDR4 spec](https://en.wikipedia.org/wiki/DDR4_SDRAM#Modules) looks less intimidating. 
* [Article: Memory Bandwidth. Napkin Math](https://www.forrestthewoods.com/blog/memory-bandwidth-napkin-math/) - how to benchmark RAM throughput and how is it in comparison with theoretical limits. 

#### Videos

* [The Trouble with Memory](https://www.recallact.com/presentation/trouble-memory)

## CPU

* [Reference Book: Intel® 64 and IA-32 ArchitecturesOptimization Reference Manual](https://software.intel.com/content/dam/develop/public/us/en/documents/64-ia-32-architectures-optimization-manual.pdf)
* [Book: Is Parallel Programming Hard, And, If So,What Can You Do About It?](https://mirrors.edge.kernel.org/pub/linux/kernel/people/paulmck/perfbook/perfbook.2019.12.22a.pdf)
* [Paper: Locating  Cache  Performance  Bottlenecks  Using  Data  Profiling](https://people.csail.mit.edu/nickolai/papers/pesterev-dprof.pdf)
* [Paper: Performance Tuning for Low-Latency Applications](https://s3-eu-west-1.amazonaws.com/aitusoftware-doc-public/downloads/PerformanceTuningHandbook.pdf)
* [Paper: Memory Barriers: a Hardware View for Software Hackers](http://www.rdrop.com/~paulmck/scalability/paper/whymb.2009.04.05a.pdf)
#### Videos

* [Presentation: Understanding CPU Microarchitecture to Increase Performance](https://www.infoq.com/presentations/microarchitecture-modern-cpu/)

#### Misc:

* [Excellent article on Load average by Brendan Gregg](http://www.brendangregg.com/blog/2017-08-08/linux-load-averages.html)

## GPU

* [Book: Understanding Latency Hiding on GPUs](https://www2.eecs.berkeley.edu/Pubs/TechRpts/2016/EECS-2016-143.pdf) - everything you need to know about GPU

## Disks
* Chapter 9 in [Systems Performance: Enterprise and the Cloud](https://www.amazon.com/Systems-Performance-Enterprise-Brendan-Gregg/dp/0133390098) is great
* [Blog posts series: Coding for SSDs](http://codecapsule.com/2014/02/12/coding-for-ssds-part-1-introduction-and-table-of-contents/) - meh. but gives you the basics

## Networking

* [Book: Computer Networking: A Top-Down Approach](https://www.amazon.com/Computer-Networking-Top-Down-Approach-7th/dp/0133594149)
* [Book: High Performance Browser Networking](https://hpbn.co/) - reads like "computer networking, but down-to-top approach". More focused on the most recent developments, while not diving too deep into fundamentals
* [Article: How to Calculate TCP throughput for long distance WAN links](http://bradhedlund.com/2008/12/19/how-to-calculate-tcp-throughput-for-long-distance-links/)
* [Twitter thread on TCP optimizations](https://threadreaderapp.com/thread/1099086415671877633.html)
* [Paper: Fundamental Limits of Online Network-Caching](https://arxiv.org/abs/2003.14085)

## Performance tunning 

* [Book: Systems Performance: Enterprise and the Cloud](https://www.amazon.com/Systems-Performance-Enterprise-Brendan-Gregg/dp/0133390098)
* [Long article: Theoretical performance guide](http://sled.rs/perf)
* [Book: Every Computer Performance Book: How to Avoid and Solve Performance Problems  on The Computers You Work With](https://www.amazon.com/gp/product/1482657759/)

#### Videos: 
* [Peddle the Pedal to the Metal](https://www.infoq.com/presentations/programming-c-efficient-scalable-software/?utm_campaign=infoq_content&utm_source=twitter&utm_medium=feed&utm_term=development)

## Performance analysis

* [Book: The Art of Computer Systems Performance Analysis: Techniques for Experimental Design, Measurement, Simulation, and Modeling](https://www.amazon.com/Art-Computer-Systems-Performance-Analysis/dp/0471503363)
* [Book: Guerrilla Capacity Planning: A Tactical Approach to Planning for Highly Scalable Applications and Services](https://www.amazon.com/Guerrilla-Capacity-Planning-Tactical-Applications/dp/3540261389)
* [Book: Analyzing Computer System Performance with Perl::PDQ](https://www.amazon.com/gp/product/B00FC99QUO/ref=dbs_a_def_rwt_hsch_vapi_tkin_p1_i0)
* [Book: Performance Modeling and Design of Computer Systems: Queueing Theory in Action](https://www.amazon.com/Performance-Modeling-Design-Computer-Systems)

#### Videos:
* [MAP6264 - Queueing Theory](https://www.youtube.com/playlist?list=PL59NBu6N8dUqYClaKpoozyzK3Kpcm5eou)  + [textbook](http://www.cse.fau.edu/~bob/courses/map6264/)

## Misc

* [Curated list about computer architecture](https://github.com/MattPD/cpplinks/blob/master/comparch.md)
