---
title: "DBEst: Revisiting approximate query processing engines with machine learning models"
collection: publications
permalink: /publication/2009-sigmod
excerpt: 'AQP Engine.'
date: 2019-7-01
venue: 'Proceedings of the 2019 International Conference on Management of Data (SIGMOD 2019)'
paperurl: 'https://wrap.warwick.ac.uk/115961/7/WRAP-DBEst-revisiting-approximate-query-processing-engines-machine-learning-models-Triantafillou-2019.pdf'
citation: 'Ma, Qingzhi, and Peter Triantafillou. "Dbest: Revisiting approximate query processing engines with machine learning models." In Proceedings of the 2019 International Conference on Management of Data, pp. 1553-1570. 2019.'
---

In the era of big data, computing exact answers to analyt-
ical queries becomes prohibitively expensive. This greatly
increases the value of approaches that can compute effi-
ciently approximate, but highly-accurate, answers to analyt-
ical queries. Alas, the state of the art still suffers from many
shortcomings: Errors are still high, unless large memory in-
vestments are made. Many important analytics tasks are not
supported. Query response times are too long and thus ap-
proaches rely on parallel execution of queries atop large big
data analytics clusters, in-situ or in the cloud, whose acqui-
sition/use costs dearly. Hence, the following questions are
crucial: Can we develop AQP engines that reduce response
times by orders of magnitude, ensure high accuracy, and
support most aggregate functions? With smaller memory
footprints and small overheads to build the state upon which
they are based? With this paper, we show that the answers
to all questions above can be positive. The paper presents
DBEst1 , a system based on Machine Learning models (re-
gression models and probability density estimators). It will
discuss its limitations, promises, and how it can complement
existing systems. It will substantiate its advantages using
queries and data from the TPC-DS benchmark and real-life
datasets, compared against state of the art AQP engines.
