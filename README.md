# NYPD-Stop-Frisk-Data-Analysis

New York City's stop and frisk policy was found to be unconstitutional by a federal judge in 2013 (Floyd v. City of New York) on the grounds that it violated the Fourth Amendment (which prohibits unreasonable searches) and Fourteenth Amendment (which prohibits racial discrimination). In the first part of this project, I used mapping techniques, applied to [stop and frisk data](https://5harad.com/data/sqf.RData), to examine some of the evidence which led to the Fourteenth Amendment ruling.

In the second part of the analysis, I concluded our analysis of whether the stop and frisk policy was racially discriminatory, from a different angle than the previous mapping analysis. I relied heavily on logistic regression and regularized regression.

From both analyses, we see that White pedestrians have the lowest rate of being stopped, and Black pedestrians have the highest rate of being stopped regardless of the threshold. 

![alt text](https://github.com/hltro/NYPD-Stop-Frisk-Data-Analysis/blob/main/fraction-stopped-vs-probability-of-weapon-possession.png)

This graph is evidence for Fourteenth Amendment violations (racial discrimination) for the following reasons:
1) No matter if the threshold is 2% or 5%, White pedestrians have a much lower rate of being stopped and frisked compared to other populations. When we look closely at the 2% threshold, all three other races have almost double or triple the fraction of being stopped, showing that the police's decision to stop and frisk is highly racially motivated and biased towards White population.
2) As the threshold value increases, the line for White pedestrains increases at a much slower rate compared to Black and Hispanic populations. This indicates that even as the probability of finding a weapon becomes higher, police is still less inclined to stop White population and more willing to stop Black, Hispanic, and Asian population. 
