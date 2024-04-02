---
title: "PGMJoins: Random Join Sampling with Graphical Models"
collection: publications
permalink: /publication/2021-2-sigmod
excerpt: 'Join Queries; Random sampling; PGMs for data management.'
date: 2021-7-01
venue: 'Proceedings of the 2021 International Conference on Management of Data (SIGMOD 2021)'
paperurl: 'https://dl.acm.org/doi/abs/10.1145/3448016.3457302'
citation: 'Shanghooshabad, Ali Mohammadi, Meghdad Kurmanji, Qingzhi Ma, Michael Shekelyan, Mehrdad Almasi, and Peter Triantafillou. "Pgmjoins: Random join sampling with graphical models." In Proceedings of the 2021 International Conference on Management of Data, pp. 1610-1622. 2021.'
---

Modern databases face formidable challenges when called to join
(several) massive tables. Joins (especially when entailing many-to-
many joins) are very time- and resource-consuming, join results
can be too big to keep in memory, and performing analytics/learn-
ing tasks over them costs dearly in terms of time, resources, and
money (in the cloud). Moreover, although random sampling is a
promising idea to mitigate the above problems, the current state
of the art leaves lots of room for improvements. With this paper
we contribute a principled solution, coined 𝑃𝐺𝑀 𝐽𝑜𝑖𝑛𝑠. 𝑃𝐺𝑀 𝐽𝑜𝑖𝑛𝑠
adapts Probabilistic Graphical Models to deriving provably random
samples of the join result for (n-way) key-joins, many-to-many joins,
and cyclic and acyclic joins. 𝑃𝐺𝑀 𝐽𝑜𝑖𝑛𝑠 contributes optimizations
both for deriving the structure of the graph and for PGM inference.
It also contributes a novel Sum-Product Message Passing Algorithm
(SP-MPA) to make a uniform sample of the joint distribution (join
result) efficiently and a novel way to deal with cyclic joins. Despite
the use of PGMs, the learned joint distribution is not approximated
and the uniform samples are drawn from the true distribution. Our
experimentation using queries and datasets from TPC-H, JOB, TPC-
DS, and Twitter shows 𝑃𝐺𝑀 𝐽𝑜𝑖𝑛𝑠 to outperform the state of the
art (by 2X–28X).
