# How fair were COVID-19 restriction decisions? A data-driven investigation of England using the dominance-based rough sets approach

For more information see the Pre-print available at arxiv at https://arxiv.org/abs/2211.00056

For any questions, suggestions, or comments please contact: abel@sdu.dk

During the COVID-19 pandemic, several countries began defining and utilising more granular restrictions based on geographical areas, instead of continuing with country wide restrictions. The UK government defined a tiered restriction system for which they defined a set of criteria to use to determine Tier assignments (T1 to T4) of different geographical areas, where the lower the tier the less restrictive the restrictions were. 
Although the set of criteria was published the inner workings used for actual assignment of tiers was somewhat opaque. As a result, the allocation of tiers suffered from a lack of transparency, leading to accusations of unfair decision making.

The set of criteria are:

| Criterion | Name | Description |
| ------------- | ------------- | ------------- |
| C1 | Number of Daily Covid cases (all ages) | A measure of the number of cases within a given 24-hour time frame for a given geographical area|
| C2 | Number of Daily Cases in over 60s | A measure of the number of cases within a given 24-hour time frame (for a given geographical area) where the patient was over sixty years old |
| C3 | Rate of change of daily cases | A measure of the rate of change of the number of cases between one 24-hour time frame and the next |
| C4 | Positivity rate | A measure of the number of positive cases that are detected as a percentage of all the tests taken within a given 24-hour time frame |
| C5 | Pressure on the NHS | An indication of the pressure that the cases are having on the NHS infrastructure for a given geographical area|

Through various data acquisition, integration, and processing (for details see see the [arxiv PrePrint](https://arxiv.org/abs/2211.00056)) a dataset was curated denoting the criteria data, for the different geographical areas, over the whole time frame that the UK tier's system was in place (The curated dataset will be available in this repository soon). 

The dominance-based rough set approach (DRSA) was then utilised to explore the fairness of the explainability of the tired system. (for details of this approach and the findings see the [arxiv PrePrint](https://arxiv.org/abs/2211.00056))
