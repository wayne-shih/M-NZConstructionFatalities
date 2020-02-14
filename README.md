# New Zealand Construction Fatalities; stats; 2016-2019

Data sourced from WorkSafe New Zealand New Zealand Mahi Haumaru Aotearoa (WorkSafe) and Statistics New Zealand Tatauranga Aotearoa (StatsNZ).

Throughout 2019 the number of fatalities in the construction sector were much higher than previous years:

### Fatalities in the Construction Industry, 2016-19
![Graph of WorkSafe Fatalities in the Construction Industry, 2016-19](/docs/worksafeConstructionFatalities2016-19.svg)

### Rate of Fatalities
| Year | Worker fatalities per 100,000 workers in NZ |
| :--: | ------------------------------------------: |
| 2016 | 2.68                                        |
| 2017 | 3.79                                        |
| 2018 | 2.47                                        |
| 2019 | **6.29**                                    |

Using *WorkSafe*’s “Fatalities” dataset with the date range of Jan 2016 to Oct 2019 and filtered by the construction industry (*ANZSIC06 Industry Classification – E: Construction*) workers (ie. excluding fatalities of members of the public as a result of someone else’s work activity). As of the writing of this report, data after October are not yet available in the dataset – due to the 3 months lag implemented to accommodate for potential additional figures from ACC claims or incidents that have not yet been reported. November and December figures have been sourced from the “Fatalities Summary Table” which are based on initial notifications to WorkSafe and lack the specificity of whether the fatality was acting as a worker or a member of the public during the incident. 

The total number of construction workers in 2016, 2017, 2018 and 2019 are approximately the same. Using *StatsNZ*’s “Household Labour Force Survey” datasets [*HLFA.SJC1EE*, *HLFA.SJC2EE* and *HLFQ.SJCSE3EE*] the estimated construction workers (*ANZSIC06 Industry Classification – E: Construction*) working in New Zealand during 2016 are `225,775(±12,800)`, 2017 are `237,250(±12,450)`, 2018 are `242,625(±14,450)`, 2019 are `238,53̄3̄(±12,73̄3̄)`. These figures have been averaged out from the March, June, September, and December estimation data with the exception where 2019 does not include the December estimation data as it was not available during the writing of this report.

## Sources
WorkSafe New Zealand, 2019. Fatalities \[dataset\]. Retrieved from [data.worksafe.govt.nz](https://data.worksafe.govt.nz/graph/detail/fatalities) on 2020, Jan 21.

WorkSafe New Zealand, 2020. Fatalities summary table. Retrieved from [data.worksafe.govt.nz](https://data.worksafe.govt.nz/editorial/fatalities_summary_table) on 2020, Jan 21.

Statistics New Zealand, 2019. Household Labour Force Survey – Persons Employed by Sex by Industry, ANZSIC06 \[dataset\]. HLFA.SJC1EE, HLFA.SJC2EE. Retrieved from http://localhost:9000/snzts/v1/dataset?format=csv&subjectCode=HLF&familyCode=SJC&familyNbr=3478&limit=100 via [\[snzts @ 3f0df40\]](https://github.com/cmhh/snzts/tree/3f0df408352def9356646c63686485d4489d7bb8) on 2020, Jan 21.

Statistics New Zealand, 2019. Household Labour Force Survey – Persons Employed by Sex by Industry, ANZSIC06 – Sampling Errors \[dataset\]. HLFQ.SJCSE3EE. Retrieved from http://localhost:9000/snzts/v1/dataset?format=csv&subjectCode=HLF&familyCode=SJC&familyNbr=4333&limit=100 via [\[snzts @ 3f0df40\]](https://github.com/cmhh/snzts/tree/3f0df408352def9356646c63686485d4489d7bb8) on 2020, Jan 21.
