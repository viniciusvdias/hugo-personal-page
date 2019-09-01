---
title: "Watershed-ng: an extensible distributed stream processing framework"
date: 2016-01-01
publishDate: 2019-09-01T20:21:24.414406Z
authors: ["Rodrigo Rocha", "Bruno Hott", "Vinícius Dias", "Renato Ferreira", "Wagner Meira", "Dorgival Guedes"]
publication_types: ["2"]
abstract: "Summary Most high-performance data processing (a.k.a. big data) systems allow users to express their computation using abstractions (like MapReduce), which simplify the extraction of parallelism from applications. Most frameworks, however, do not allow users to specify how communication must take place: That element is deeply embedded into the run-time system abstractions, making changes hard to implement. In this work, we describe Wathershed-ng, our re-engineering of the Watershed system, a framework based on the filter–stream paradigm and originally focused on continuous stream processing. Like other big-data environments, Watershed provided object-oriented abstractions to express computation (filters), but the implementation of streams was a run-time system element. By isolating stream functionality into appropriate classes, combination of communication patterns and reuse of common message handling functions (like compression and blocking) become possible. The new architecture even allows the design of new communication patterns, for example, allowing users to choose MPI, TCP, or shared memory implementations of communication channels as their problem demands. Applications designed for the new interface showed reductions in code size on the order of 50% and above in some cases. The performance results also showed significant improvements, because some implementation bottlenecks were removed in the re-engineering process. Copyright © 2016 John Wiley & Sons, Ltd."
featured: false
publication: "*Concurrency and Computation: Practice and Experience*"
tags: ["distributed systems", "watershed", "big data", "frameworks"]
url_pdf: "https://onlinelibrary.wiley.com/doi/abs/10.1002/cpe.3779"
doi: "10.1002/cpe.3779"
---

