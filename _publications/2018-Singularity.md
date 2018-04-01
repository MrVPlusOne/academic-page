---
title: "Singularity: Pattern Fuzzing for Worst Case Complexity"
collection: publications
permalink: /publication/2018-singularity
excerpt: 'A new blackbox complexity testing technique for determining the worst-case asymptotic complexity of a given application.'
date: 2018-03-10
venue: 'Under submission'
paperurl: ''
citation: 'Jiayi Wei, Jia Chen, Yu Feng, Kostas Ferles, and Isil Dillig. (2018). &quot;Singularity: Pattern Fuzzing for Worst Case Complexity.&quot; <i>ESEC/FSE</i>.'
---
We describe a new blackbox complexity testing technique for determining the worst-case asymptotic complexity of a given application. The key idea is to look for an input pattern —rather than a concrete input— that maximizes the asymptotic resource usage of the program. Because input patterns can be described concisely as programs in a restricted language, our method transforms the complexity testing problem to optimal program synthesis. In particular, we express these input patterns using a new model of computation called Recurrent Computation Graph (RCG) and solve the optimal synthesis problem by developing a genetic programming algorithm that operates on RCGs.
