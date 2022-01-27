# apc_fairness
**Overview:** Assessing the impacts of age, period, and cohort on how Americans perceive whether others will treat them fairly

**Description:** This was a lab for the graduate course "Time Series, Panel Data, and Forecasting." In it, I assess the impacts of age, period, and cohort on the *fair* variable in the General Social Survey (GSS) which asks Americans, "Do you think most people would try to take advantage of you if they got a chance, or would they try to be fair?" Because this question is asked several times between 1972 and 2012, shifts in response to the *fair* variable may be attributed to age (how old a respondent is when they take the survey), period (the year a respondent takes the survey), and/or cohort (the year a respondent was born). For example, a 50 year old taking the survey in 2002 may answer a particular way because they are middle aged, because they are taking the survey in the early 2000s, and/or because they were born in the 1950s.

In addition to the analysis, some data cleaning steps are taken. In particular, I create age, period, and cohort categories to simplify the analysis.

**Packages Used:**
- ggplot2
- plyr
- rms
- Epi
- tidyverse
- QMSS
