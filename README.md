[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/COMP4447TEAM/crime/main)

This repository contains 20 files:

-a Jupyter notebook

-12 original data files, 11 csv and 1 tsv (prisoner demographics, us population, 10 crime rate files)

-a text file with requirements (for the binder link)

-this README.md file

-5 files created by the Jupyter notebook (3 csv and 2 pickle files)


The dataframed used in the final data analysis consists of 39 observations and 30 attributes.

The attributes are:

1)Years	Calendar year of observation	int64

2)TotalPrisoners	All state and federal inmates held in prison or jail in the United States as of Dec 31st	int64

3)TotalAdmits	Total number of inmates sentenced to more than one year in the year of observation	int64

4)TotalReleases	Total number of inmates released (under sentences of more than one year) in the year of observation	int64

5)TotalUSPop	The population of the United States from the US Census in census years and from statistical estimates in non-census years	int64

6)DUI	Arrest rates per 100,000 population units in the observation year for Driving under the influence	float64

7)curfew_loitering	Arrest rates per 100,000 population units in the observation year for Curfew and loitering	float64

8)disorderly_conduct	Arrest rates per 100,000 population units in the observation year for Disorderly conduct	float64

9)drug_violations	Arrest rates per 100,000 population units in the observation year for Drug abuse violations	float64

10)drunkenness	Arrest rates per 100,000 population units in the observation year for Drunkenness	float64

11)liquor	Arrest rates per 100,000 population units in the observation year for Liquor laws	float64

12)property	Arrest rates per 100,000 population units in the observation year for Property crime	float64

13)vagrancy	Arrest rates per 100,000 population units in the observation year for Vagrancy	float64

14)violence	Arrest rates per 100,000 population units in the observation year for Violent Crimes	float64

15)weapons	Arrest rates per 100,000 population units in the observation year for Weapons	float64

16)SentGT1Yr	Number of inmates as of Dec 31st with a total maximum sentence of more than 1 year	int64

17)SentLT1Yr	Number of inmates as of Dec 31st with a total maximum sentence of 1 year or less	int64

18)Unsentenced	Number of inmates as of Dec 31st that were unsentenced	int64

19)AdmitProbation	Number of inmates sentenced to a year or more in the year of observation for new court commitments including probation violators	int64

20)AdmitParole	Number of inmates sentenced to a year or more in the year of observation for parole violations	int64

21)AdmitOCR	Number of inmates sentenced to a year or more in the year of observation for other conditional release violations	int64

22)TotPrisonerRate	TotalPrisoners divided by (TotalUSPop divided by 100,000) i.e. rate per 100,000	float64

23)TotAdmitRate	TotalAdmits divided by (TotalUSPop divided by 100,000) i.e. rate per 100,000	float64

24)TotReleaseRate	TotalReleases divided by (TotalUSPop divided by 100,000) i.e. rate per 100,000	float64

25)SentGT1YrRate	SentGT1Yr divided by (TotalUSPop divided by 100,000) i.e. rate per 100,000	float64

26)SentLT1YrRate	SentLT1Yr divided by (TotalUSPop divided by 100,000) i.e. rate per 100,000	float64

27)UnsentRate	Unsentenced divided by (TotalUSPop divided by 100,000) i.e. rate per 100,000	float64

28)AdmProbRate	AdmitProbation divided by (TotalUSPop divided by 100,000) i.e. rate per 100,000	float64

29)AdmitParoleRate	AdmitParole divided by (TotalUSPop divided by 100,000) i.e. rate per 100,000	float64

30)AdmitOCRRate	AdmitOCR divided by (TotalUSPop divided by 100,000) i.e. rate per 100,000	float64


DATA SOURCES:

United States. Bureau of Justice Statistics. National Prisoner Statistics, [United States], 1978-2018. ICPSR37639-v1. Ann Arbor, MI: Inter-university Consortium for Political and Social Research [distributor], 2020-07-23. http://doi.org/10.3886/ICPSR37639.v1US Population Data Set (usa_df)

USAFacts at https://usafacts.org/data/topics/people-society/population-and-demographics/population-data/population/ 

OJJDP Statistical Briefing Book. Trends in the number of arrests by race for All offenses. Available: https://www.ojjdp.gov/ojstatbb/crime/ucr_trend.asp?table_in=2 . Released on November 16, 2020.
