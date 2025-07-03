CAP Theorem
The CAP Theorem (also known as Brewer's Theorem) states that in any distributed data system, it is impossible to simultaneously guarantee all three of the following properties:

Consistency (C):
Every read operation receives the most recent write or an error. 

Availability (A):
Every request receives a non-error response, without the guarantee that it contains the most recent write. A system should always remain responsive, even if it returns stale data.

Partition Tolerance (P):
The system continues to function despite arbitrary partitioning due to network failures. A partition refers to the loss of communication between parts of the system. To achieve partition tolerance, data replication across nodes is essential.

Trade-offs in Distributed Systems
According to the CAP Theorem, a distributed system can only achieve two of the above three properties at any given time. The third must be compromised. Based on the system’s design goals and use case, the trade-offs are as follows:

Consistency + Partition Tolerance (CP):
The system remains consistent and tolerant to network partitions, but availability may be sacrificed. That means some requests might not be served during network failures.

Availability + Partition Tolerance (AP):
The system stays available and resilient to partitions, but consistency may be compromised. Some nodes may return outdated or inconsistent data.

Consistency + Availability (CA):
The system ensures consistency and availability only in the absence of partitions. In real-world distributed systems, this combination is impractical because partition tolerance is typically non-negotiable.

Key Insight
In practical distributed system design, Partition Tolerance is considered a non-negotiable requirement. Therefore, the typical design decision lies between favoring Consistency or Availability, based on specific business or application needs.
