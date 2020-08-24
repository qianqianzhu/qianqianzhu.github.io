---
layout: post
title:  "Lessons Learned from a Literature Survey on the Application of Mutation Testing"
date:   2016-10-13
categories: research
---
We conducted a systematic literature review (SLR) on mutation testing, with a particular focus on the understanding of how people actually apply mutation testing and how they cope with the well-known limitations of mutation testing, e.g., the cost to generate mutants. Our systematic literature review is based on a collection of 191 papers from 22 venues published between 1981 and 2015. We identified and classified the main applications of mutation testing, and also analysed the level of replicability of empirical studies related to mutation testing. Particularly, we characterised these studies on the basis of seven facets, including in which testing activities mutation testing is used, which mutation tools and which mutation operators are employed, and how the core inherent problems of mutation testing, i.e. the equivalent mutant problem and the high computational cost, are addressed during the actual usage.

![image](https://qianqianzhu.github.io/images/aspects.png)

### Important take-aways from the Literature Survey
1. Supporting techniques are under development
  Many of the supporting techniques for making mutation testing applicable are still under-developed. Also, existing mutation tools are not complete concerning the mutation operators they offer. The two inherent problems of mutation testing, especially the equivalent mutant detection problem, are not well-solved in the context of our research body. For the equivalent mutant problem, manual analysis ranked the top 1 among the others.
2. A deeper understanding is required
  A deeper understanding of mutation testing is required, such as what particular kinds of faults mutation testing are good at finding, and how a certain type of mutant work when testing real software. This would help the community to develop new mutation operators as well as overcome some of the inherent challenges.
3. Raise the awareness of appropriately reporting mutation testing
 The awareness of appropriately reporting mutation testing in testing experiments should be raised among the researchers. We analysed 191 papers where around half percent did not provide their mutation tool source and subject program source. We considered the following five elements to be essential: mutation tool source, mutation operators used in experiments, how to deal with the equivalent mutant problem, how to cope with high computational cost and subject program source.
