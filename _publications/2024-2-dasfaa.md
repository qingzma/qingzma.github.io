---
title: "Segam: Secure and Efficient Group-by-Aggregation Queries across Multiple Private Database"
collection: publications
permalink: /publication/2024-2-dasfaa
excerpt: 'Group-by-Aggregation Queries'
date: 2024-07-02
venue: 'The International Conference on Database Systems for Advanced Applications (DASFAA)'
paperurl: 'https://www.dasfaa2024.org/'
citation: 'Zicheng Cao, Qingzhi Ma, Wei Chen, Lei Zhao, An Liu. "Segam: Secure and Efficient Group-by-Aggregation Queries across Multiple Private Database". The International Conference on Database Systems for Advanced Applications (DASFAA), July 2nd. 2024.'
---

Data sharing faces significant constraints with business competition intensifying and privacy regulations enacted. Secure collaborative analysis, particularly in group-by-aggregation queries, has gained significant attention as a way to perform data analysis without directly sharing data among multiple data owners. Previous work has explored outsourced databases, computing, and interactive approaches, but they all have limitations. Outsourced approaches rely on multiple third-party servers, limiting practicality. Interactive approaches can avoid this limitation, but existing solutions have lower efficiency for group-by-aggregation queries.
In this paper, we propose Segam, a secure collaborative analytics system designed to execute group-by-aggregation queries across multiple private databases. We leverage Shamir's secret sharing scheme to design secure operators, ensuring that sensitive data remains confidential. To strike a balance between efficiency and security, we adopt a query decomposition strategy, transforming the execution into a multi-round process that combines both plaintext and secure operators. Our comprehensive experiments validate Segam's efficiency and usability, showing impressive performance improvements of at least 101.0x in time consumption and 8,186.6x in communication costs compared to previous open-source work. 
