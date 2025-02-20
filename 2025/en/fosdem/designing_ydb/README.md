# Designing YDB: Constructing a Distributed cloud-native DBMS for OLTP and OLAP from the Ground Up

**Speaker:** [Evgenii Ivanov](https://www.linkedin.com/in/eivanov89/)\
**Slides:** [presentation.pdf](presentation.pdf)\
**Video recording:** [YouTube](https://youtu.be/fMR6zQVchgE?si=kqM_b7FHiYAnTZHg)\
**Event:** [FOSDEM 2025 (Cloud Native Databases Track)](https://fosdem.org/2025/schedule/event/fosdem-2025-5374-designing-ydb-constructing-a-distributed-cloud-native-dbms-for-oltp-and-olap-from-the-ground-up/)

Distributed systems are great in multiple aspects: they are built to be fault tolerant and reliable, can scale almost infinitely, provide low latency in geo-distributed scenarios and, finally, they are geeky and fun to explore. YDB is an open source distributed SQL database which has been running production for years. There are installations with thousands of servers storing petabytes of data. To provide these capabilities, any distributed DBMS must achieve consistency and consensus while tolerating unreliable networks, faulty hardware and absence of a global clock.

In this session, we will provide a gentle introduction to problems, challenges and fallacies of distributed computing, explaining why sharded systems like Citus are not always ACID and differ from truly distributed systems. Then, we will dive deep into the design decisions made by YDB to address these difficulties and sketch YDB's architecture layer by layer - from the bare metal disks and distributed storage up to OLTP and OLAP functionalities. At the end, we will briefly compare our approach with that of Calvin, which originally inspired YDB, and Spanner.
