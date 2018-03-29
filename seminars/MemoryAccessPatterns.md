---
layout: page
Understanding Object-level Memory Access Patterns (and Are HPC Applications Different?)

permalink: /seminars/MemoryAccessPatterns/
date: October 25, 2017
---

## Understanding Object-level Memory Access Patterns (and Are HPC Applications Different?)


### Speaker:

[Xiaosong Ma]()

### Abstract:

Memory accesses limit the performance and scalability of countless applications. Many design and optimization efforts will benefit from an in-depth understanding of memory access behavior, which is not offered by extant access tracing and profiling methods.

In this work, we adopt a holistic memory access profiling approach to enable a better understanding of program-system memory interactions. We have developed a two-pass tool adopting fast online and slow offline profiling, with which we have profiled, at the variable/object level, a collection of 38 representative applications spanning major domains (HPC, personal computing, data analytics, AI, graph processing, and datacenter workloads), at varying problem sizes. We have performed detailed result analysis and code examination. Our findings provide new insights into application memory behavior, including insights on per-object access patterns, adoption of data structures, and memory-access changes at different problem sizes. We find that scientific computation applications exhibit distinct behaviors compared to datacenter workloads, motivating separate memory system design/optimizations.
