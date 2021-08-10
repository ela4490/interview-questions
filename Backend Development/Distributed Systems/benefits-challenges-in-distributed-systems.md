Benefits and challenges of distributed systems :

There are three reasons that teams generally decide to implement distributed systems:
* Horizontal Scalability—Since computing happens independently on each node, it is easy and generally inexpensive to add additional nodes and functionality as necessary.
* Reliability—Most distributed systems are fault-tolerant as they can be made up of hundreds of nodes that work together. The system generally doesn’t experience any disruptions if a single machine fails.
* Performance—Distributed systems are extremely efficient because work loads can be broken up and sent to multiple machines.

However, distributed systems are not without challenges. Complex architectural design, construction, and debugging processes that are required to create an effective distributed system can be overwhelming.

Three more challenges you may encounter include:
* Scheduling—A distributed system has to decide which jobs need to run, when they should run, and where they should run. Schedulers ultimately have limitations, leading to underutilized hardware and unpredictable runtimes.
* Latency—The more widely your system is distributed, the more latency you can experience with communications. This often leads to teams making tradeoffs between availability, consistency, and latency.
* Observability—Gathering, processing, presenting, and monitoring hardware usage metrics for large clusters is a significant challenge.
