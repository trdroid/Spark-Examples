# Resilient Distributed Dataset (RDD)

The basic and an essential data abstraction that Spark provides is the **Resilient Distributed Dataset (RDD)**.

**Resilient**

The *Resilient (R)* in *RDD* signifies that Spark is designed to handle the scenario of node failures while data is being processed on a cluster of nodes.

**Distributed**

The *Distributed (D)* in *RDD* signifies that Spark is designed to split a big dataset into smaller buckets and distribute them to to be processed parallely on a cluster of nodes.

### Properties of RDD

The properties of Spark RDD are

* Distributable
* Immutable
* Strongly
* Memory Resident

**Memory Resident**

Spark stores RDDs in the memory as much as it can. Spark is fast at processing the data because it processes these RDDs that are in memory.

*Writing to disk*

In cases where the size of the data grows beyond the memory capacity, Spark writes data to the disk.
