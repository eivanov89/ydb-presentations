# YDB: dealing with Big Data and moving towards AI

**Speaker:** [Alexander Zevaykin](https://www.linkedin.com/in/alexander-zevaykin-6bb8162bb)\
**Slides:** [presentation.pdf](presentation.pdf)\
**Event:** [Tech Internals Conf Cyprus 2024](https://qcon.infoq.cn/2024/beijing/presentation/5807)

YDB is a versatile open-source Distributed SQL Database that combines high availability and scalability with strong consistency and ACID transactions. It provides services for ML-products and goes ahead of vector search.

**Outline**：

The database is used for industrial operations within Yandex. Among its clients, Yandex Market, Yandex Alice, and Yandex Taxi. They are some of the largest and heaviest AI-based applications.

The database provides true elastic scalability, capable of scaling up or down by several orders of magnitude.

At the same time, the database is fault-tolerant. It has been designed to work across three availability zones, ensuring that the database continues to function even if one of the zones becomes unavailable. The database automatically recovers after a disk failure, server failure, or datacenter failure, with minimal latency disruptions to the applications.

Currently, work is underway to implement accurate and approximate nearest neighbor search for machine learning purposes.

**Takeaways**：

* Architecture of a distributed fault-tolerant database.
* Approaches to the implementation of vector search on large amounts of data.