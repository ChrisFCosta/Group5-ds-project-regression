# Group5-ds-project-regression
Group Repository to work on our regression project together 
---
Hi Both I created this Repo so we could work together please feel free to add any notes here. I'm thinking once we review everything we can write our names under each of our assigned tasks below. If ever you need to reach me please feel free to write me on Discord our you can also email me if needed at chrisferreiracosta@hotmail.com.
---
For now it looks like we will be using the COVID19_Qc_RapportINSPQ_HistoVigie.csv file for our data which I placed in the Covid-Data fpolder on this repo. https://github.com/ChrisFCosta/Group5-ds-project-regression/blob/main/Covid-Data/COVID19_Qc_RapportINSPQ_HistoVigie.csv

I found the index for all of the column headers here but only in French:

https://docplayer.fr/202664831-Liste-de-variables-et-notes-methodologiques-covid-19-portrait-quotidien-des-cas-confirmes.html

Although here are a few I think we'll need translated to English:

**Nb_Cas_Cumulative:** Cumulative number of confirmed cases for all of Quebec. Confirmed cases include laboratory-confirmed cases and those confirmed by epidemiologic linkage. Cases with an unknown reporting date are not included in the roll-up by date.

**Nb_Nvx_Cas:** Number of new confirmed cases for all of Quebec according to the reporting date.

**Nb_Cas_Actifs:** Number of active cases for all of Quebec.

**Nb_Deces_Cumulatif_Total:** Cumulative number of deaths, all living environments combined, for all of Quebec. Deaths with an unknown date of death are not included in the cumulative by date.

**Nb_Nvx_Deces_Total:** Total number of new deaths for all of Quebec by date of death.


---
## Our task

Your task is to use RDD to estimate the effect of the following events in Quebec:

1. The 20/3/2020 lockdown
2. The reopening of schools on 31/8/2020
3. The 25/12/2020 lockdown

 assigned
 ### Requirements

You need to find data on at least one COVID measure for `y` (either COVID cases, hospitalizations or deaths) and provide the following for each:

- A RDD plot similar to the ones shown above
- An interpretation of the p-value on the effect of the measure taken (the cutoff parameter)
- A justification on the design of your regression:

  - The amount of time included on both sides of the cutoff (longer is not necessarily better)
  - The polynomial degree (higher is not always better)
  - Other regression design considerations

- A 2 paragraph explanation of your findings for that event.
