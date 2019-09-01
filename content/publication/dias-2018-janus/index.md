---
title: "Janus: Diagnostics and reconfiguration of data parallel programs"
date: 2018-01-01
publishDate: 2019-09-01T15:47:01.229406Z
authors: ["Vinicius Dias", "Wagner Meira", "Dorgival Guedes"]
publication_types: ["2"]
abstract: "The increasing amount of data being stored and the variety of algorithms proposed to meet processing demands of the data scientists have led to a new generation of computational environments and paradigms. These environments simplify the task of programmers, but achieving the ideal performance continues to be a challenge. In this work we investigate important factors concerning the performance of common big-data applications and consider the Spark framework as the target for our contributions. Based on that, we present the design and implementation of Janus, a tool that automates the reconfiguration of Spark applications. It leverages logs from previous executions as input, enforces configurable adjustment policies over the collected statistics and makes its decisions taking into account communication behaviors specific of the application evaluated. In order to accomplish that, Janus identifies global parameters that should be updated, or points in the user program where the data partitioning can be adjusted based on those policies. Our results show gains of up to 1.9× in the scenarios considered."
featured: false
publication: "*Journal of Parallel and Distributed Computing*"
tags: ["Performance diagnosis", "Dynamic reconfiguration", "Spark"]
url_pdf: "http://www.sciencedirect.com/science/article/pii/S0743731518301084"
doi: "10.1016/j.jpdc.2018.02.030"
---

