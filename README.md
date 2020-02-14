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

## Data Sources of the Dataset & Limitations

### WorkSafe Fatalities
> The information in this report comes from two sources: 
>
> WorkSafe New Zealand Fatalities Register:
> 1. Includes information based on confirmed fatal work-related incidents reported to WorkSafe. 
> 2. Accident Compensation Corporation Te Kaporeihana Āwhina Hunga Whara (ACC) claims:
>    * Includes information based on accepted ACC claims for work-related fatalities.  
>    * This can include work-related fatalities that come under the Maritime New Zealand Nō te rere moana Aotearoa, Civil Aviation Authority Te Mana Rererangi Tūmatanui o Aotearoa, and New Zealand Police Nga Pirihimana o Aotearoa jurisdictions. 
>
> This data takes time to stabilise. We recommend applying a three month lag to the fatality number.
>
> * Employment data for fatality rates are based on Linked Employer-Employee Data (LEED). There is an 18 month lag on this data. We assume that employment this year is unchanged from last year in order to estimate fatality rates for this year.
> * A single fatality may have several accident types.
> * Averages have been rounded to 1 decimal place. A value of ‘0’ indicates a value that has been rounded to ‘0.0’.
> * The AFF2017 variable uses the Australia and New Zealand Standard Industry Classification (2006) system, but alters the reporting levels of the Agriculture, Forestry and Fishing industry to provide more detail.
> * Data quality has improved over time so caution is advised when interpreting the data.
[data.worksafe.govt.nz](https://data.worksafe.govt.nz/graph/detail/fatalities)

### StatsNZ Household Labour Force Survey (HLFS)
> The target population is the entire group from which you would ideally like to get information. The target population for the HLFS is the working-age population of New Zealand. We define this as ‘the non-institutionalised population 15 years and over, who usually live in New Zealand.’ Specifically the target population excludes:
> * people who have been living in New Zealand for less than 12 months, and who do not propose to stay in New Zealand for a total of 12 months or more
> * long-term residents of homes for older people, hospitals, and psychiatric institutions (long-term is defined as six weeks or more)
> * people in prison.
>
> The survey population consists of the group members (from the target population) who have a chance of being selected as part of the sample (ie they can be identified through the sampling frame). For the HLFS, we apply further exclusions to the target population to create the survey population (often due to cost and practical reasons), from which we then select the HLFS sample. These exclusions are a small percentage of the population and the bias introduced is minimal. The survey population is the target population with these exclusions. People:
> * residing in non-private dwellings (eg. people in hotels, motels, hostels, military camp)
> * residing in non-permanent dwellings (eg. people in tents or caravans not permanently sited)
> * residing at a wharf or landing place (eg. people in ships, boats)
> * residing on islands other than the North, South, and Waiheke islands (eg. people on Great Barrier, Kawau, Chatham, and Stewart islands).
>
> Sampling errors quantify the variability that occurs by chance because a sample rather than an entire population is surveyed. We calculate sampling errors using the jackknife method. It is based on the variation between estimates of different subsamples taken from the whole sample. This is an attempt to see how estimates would vary if we were to repeat the survey with new samples of individuals. We produce sampling errors and confidence intervals for most point and change estimates. Confidence intervals are used to demonstrate the amount of uncertainty associated with a sample estimate; presenting an upper and lower limit for a particular estimate. The HLFS calculates confidence intervals at the 95 percent confidence level, which means that if multiple samples were drawn, 95% of the confidence intervals would contain the true figure. As the size of the sampled group decrease, the relative sampling errors will generally increase. For example, the estimated number of Pacific peoples employed would have a larger relative sampling error than the estimated total number of people employed. Likewise, the estimated number of people unemployed would have a larger relative sampling error than the estimated number of people employed. A change in an estimate, either from one adjacent quarter to the next, or between quarters a year apart, is said to be statistically significant if it is larger than the associated sampling error.
```
<r:URN> urn:ddi:nz.govt.stats:6a13af44-0057-4a63-835a-c1a0c6f8ef91:16 </r:URN>
<r:Agency> nz.govt.stats </r:Agency>
<r:ID> 6a13af44-0057-4a63-835a-c1a0c6f8ef91 </r:ID>
<r:Version> 16 </r:Version>
```
[datainfoplus.stats.govt.nz](http://datainfoplus.stats.govt.nz/Item/nz.govt.stats/b7c39358-aa03-446f-a27d-91c37caac35d?&_ga=2.19847480.1830762553.1581720966-1074207774.1579492621#/nz.govt.stats/6a13af44-0057-4a63-835a-c1a0c6f8ef91#)
