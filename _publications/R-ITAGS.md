---
title: "Risk-Tolerant Task Allocation and Scheduling in Heterogeneous Multi-Robot Teams"
collection: publications
category: conferences # conferences # manuscripts
permalink: /publication/R-ITAGS
# excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
date: 2023-10-01
venue: 'IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)'
# slidesurl: 'https://jinwoop.github.io/files/slides1.pdf'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/10341837'
bibtexurl: 'https://jinwoop.github.io/files/bib/R-ITAGS.bib'
citation: 'J. Park, A. Messing, H. Ravichandar and S. Hutchinson, "Risk-Tolerant Task Allocation and Scheduling in Heterogeneous Multi-Robot Teams," 2023 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS), Detroit, MI, USA, 2023, pp. 5372-5379, doi: 10.1109/IROS55552.2023.10341837.'
---
Effective coordination of heterogeneous multi-robot teams requires optimizing allocations, schedules, and motion plans in order to satisfy complex multi-dimensional task requirements. This challenge is exacerbated by the fact that real-world applications inevitably introduce uncertainties into robot capabilities and task requirements. In this paper, we extend our previous work on trait-based time-extended task allocation to account for such uncertainties. Specifically, we leverage the Sequential Probability Ratio Test to develop an algorithm that can guarantee that the probability of failing to satisfy task requirements is below a user-specified threshold. We also improve upon our prior approach by accounting for temporal deadlines in addition to synchronization and precedence constraints in a Mixed-Integer Linear Programming model. We evaluate our approach by benchmarking it against three baselines in a simulated battle domain in a city environment and compare its performance against a state-of-the-art framework in a pandemic-inspired multi-robot service coordination problem. Results demonstrate the effectiveness and advantages of our approach, which leverages redundancies to manage risk while simultaneously minimizing makespan.