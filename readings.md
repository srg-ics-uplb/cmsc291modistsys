# CMSC 291(Special Topics): Modern Distributed Systems Reading List

## Foundational 
#### Time, Clocks, and Global States
* [Time, Clocks, and the Ordering of Events in a Distributed System](https://lamport.azurewebsites.net/pubs/time-clocks.pdf). Leslie Lamport, CACM 1978
* [Virtual Time and Global States of Distributed Systems](https://pages.cs.wisc.edu/~remzi/Classes/739/Fall2016/Papers/mattern89.pdf). F. Mattern, 1988.
* [Consistent Global States of Distributed Systems: Fundamental Concepts and Mechanisms](https://www.cs.utexas.edu/users/lorenzo/corsi/cs380d/papers/chapt4.pdf). O. Babaoglu and K. Marzullo. UBLCS TR 1993.
* [Distributed Snapshots: Determining Global States of Distributed Systems](https://lamport.azurewebsites.net/pubs/chandy.pdf). K. Mani Chandy and Leslie Lamport. ACM TOCS, 1985. 

 
#### Consensus
* [How to Build a Highly Available System Using Consensus](https://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.61.8330&rep=rep1&type=pdf). B. W. Lampson
* [The Part-Time Parliament](https://lamport.azurewebsites.net/pubs/lamport-paxos.pdf). ACM 1998.
* [Paxos Made Simple](https://lamport.azurewebsites.net/pubs/paxos-simple.pdf). L. Lamport. 2001
* [Paxos Made Moderately Complex](https://www.cs.cornell.edu/courses/cs7412/2011sp/paxos.pdf). R V. Renesse and D. Altinbuken.
* [In Search of an Understandable Concensus Algorithm](https://web.stanford.edu/~ouster/cgi-bin/papers/raft-atc14). D. Ongaro and J. Ousterhout. USENIX ATC 2014
* [ZooKeeper: Wait-free coordination for Internet-scale systems](https://static.usenix.org/event/usenix10/tech/full_papers/Hunt.pdf). P. Hunt et al. USENIX ATC 2010
* [Unreliable Failure Detectors for Reliable Distributed Systems](https://www.cs.utexas.edu/~lorenzo/corsi/cs380d/papers/p225-chandra.pdf). T. D. Chandra and S. Toueg.

#### Replication
* [Replication Techniques for Availability](https://www.researchgate.net/publication/221029788_Replication_Techniques_for_Availability). R. van Renesse and R. Guerraoui. 
* [Viewstamped Replication: A New Primary Copy Method to Support Highly-Available Distributed Systems](https://pmg.csail.mit.edu/papers/vr.pdf).B. Oki and B. H. Liskov. SOSP 1988.
* [Viewstamped Replication Revisited](https://pmg.csail.mit.edu/papers/vr-revisited.pdf).B. Liskov and J. Cowling.
* [Chain Replication for Supporting High Throughput and Availability](https://www.usenix.org/legacy/event/osdi04/tech/full_papers/renesse/renesse.pdf).R. van Renesse and F. B. Schneider. USENIX OSDI '04. 
* [Optimistic Replication](https://pages.lip6.fr/Marc.Shapiro/papers/Optimistic_Replication_Computing_Surveys_2005-03_cameraready.pdf). Y. Saito and M. Shapiro. ACM CS 2005.

#### Causality/Transactions
* [Linearizability: A Correctness Condition for Concurrent Objects](https://cs.brown.edu/~mph/HerlihyW90/p463-herlihy.pdf). M. P. Herlihy and J. M. Wing. ACM TOPLAS Vol. 12 No. 3 1990.
* [Detecting Causal Relationships in Distributed Computations: In Search of the Holy Grail](https://www.vs.inf.ethz.ch/publ/papers/holygrail.pdf). R. Schwarz and F. Mattern. 
* [Understanding the Limitations of Causality and Totally Ordered Communication](https://www.cs.rice.edu/~alc/comp520/papers/Cheriton_Skeen.pdf). D. R. Cheriton and D. Skeen. SOSP 1993.
* [Calvin: Fast Distributed Transactions for Partitioned Database Systems](https://www.cs.umd.edu/~abadi/papers/calvin-sigmod12.pdf). A. Thomson et al. ACM SIGMOD 2012.


#### Concurrency
*

#### Fault Tolerance
* [The Byzantine Generals Problem](https://www.cs.cornell.edu/courses/cs614/2004sp/papers/LSP82.pdf). L. Lamport et al. 
* [Implementing Fault-Tolerant Services Using the State Machine Approach: a Tutorial](https://www.cs.cornell.edu/fbs/publications/SMSurvey.pdf). F. B. Schneider.
* [Practical Byzantine Fault Tolerance](https://pmg.csail.mit.edu/papers/osdi99.pdf). M. Castro and B. Liskov. 
* [Concurrency Control and Recovery in Database Systems](https://courses.cs.washington.edu/courses/cse551/09au/papers/CSE550BHG-Ch7.pdf). P.A. Bernstein et. al. Addison-Wesley 1987.
* [MDCC: Multi-Data Center Consistency](https://amplab.cs.berkeley.edu/wp-content/uploads/2013/03/mdcc-eurosys13.pdf). R. Kriska et al. EuroSys 2013.

#### Security
*

#### Programming/Computation Models
* [MapReduce: Simplified Data Processing on Large Clusters](https://static.googleusercontent.com/media/research.google.com/en//archive/mapreduce-osdi04.pdf).J. Dean and S. GHemawat. USENIX OSDI 2004.
* [Dryad: Distributed Data-Parallel Programs from Sequential Building Blocks](https://www.microsoft.com/en-us/research/wp-content/uploads/2007/03/eurosys07.pdf). M. Isard et al. EUROSYS 2007.


#### Impossibility Results
* [Impossibility of Distributed Consensus with One Faulty Process](https://groups.csail.mit.edu/tds/papers/Lynch/jacm85.pdf).M. J. Fisher and N. A. Lynch. JACM 1985.
* [Brewer's Conjecture and the Feasibility of Consistent, Available, Partition-Tolerant Web Services](https://users.ece.cmu.edu/~adrian/731-sp04/readings/GL-cap.pdf). S. Gilbert and N. Lynch.

## Production Systems
* [The Google File System]
* [Dynamo: Amazon's Highly Available Key-Value Store]
* [Bigtable: A Distributed Storage System for Structured Data]
* [The Chubby Lock Service for Loosely-Coupled Distributed Systems]


## Miscellaneous
* [Hints for Computer System Design](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/02/acrobat-17.pdf). B. W. Lampson

## Other Lists
* [Distributed Systems Reading Group by Aleksey Charapko](http://charap.co/category/reading-group/)
* [MIT Distributed Systems Reasearch Group](http://dsrg.pdos.csail.mit.edu/papers/)
* [Dan Creswell's Distributed Systems Reading List](https://dancres.github.io/Pages/)
* [Christopher Meiklejohn Readings in distributed systems](http://christophermeiklejohn.com/distributed/systems/2013/07/12/readings-in-distributed-systems.html)
* [Prof. Murat's List of Foundational Distributed Systems Papers](https://muratbuffalo.blogspot.com/2021/02/foundational-distributed-systems-papers.html) 
* [Jaried Ririe's Readings List](https://backendology.com/2018/09/10/distributed-systems-course-reading-list/)
* [Damian Gryski's Resources for Concensus and Distribued Lock Services](https://github.com/dgryski/awesome-consensus)
