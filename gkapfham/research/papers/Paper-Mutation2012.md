---
id: -38
title: Do Redundant Mutants Affect the Effectiveness and Efficiency of Mutation Analysis?
layout: researchpaper_n
categories: [research, paper, conference, mutation testing]
authors: Ren&eacute; Just, Gregory M. Kapfhammer, and Franz Schweiggert
mapped: true
header: false
research: false
paper: true
backup: ../../../../../../
---

## {{ page.title }} [<i class="fa fa-download"></i>]({{site.baseurl}}download/research/papers/mutation2012-just-kapfhammer-schweiggert.pdf "Download this Paper!")

### {{page.authors }}

### <em>Proceedings of the 7th International Workshop on Mutation Analysis</em>, April 2012

### Abstract

Mutation analysis is an unbiased and powerful method for assessing input values and test oracles. However, in comparison
to other techniques, such as those that rely on code coverage, it is a computationally-expensive and time-consuming
method, especially for large software systems. This high cost is due, in part, to the fact that many mutation operators
generate redundant mutants that may both misrepresent the mutation score and increase the runtime of the mutation
analysis process. After showing how the conditional operator replacement (COR) mutation operator can be defined in a
redundant-free manner, this paper uses four real-world programs, ranging in size from 3,000 to nearly 40,000 lines of
code, to show the prevalence of redundant mutants. Focusing on the conditional operator replacement (COR) and relational
operator replacement (ROR) mutation operators that create 41% of all mutants in the chosen programs, the case study
reveals that the removal of redundant mutants reduces the runtime of mutation analysis by up to 34%. Additional
empirical results show that redundant mutants can lead to a mutation score that is misleadingly overestimated by as much
as 10%. Overall, this paper convincingly demonstrates that it is possible to improve the effectiveness and efficiency of
a mutation analysis system by identifying and removing redundant mutants.
