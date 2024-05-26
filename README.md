# Exploring Why Civil Resistance Works
This is an EDA and statistical analysis project, on which we replicate some of the findings from the influential book [Why Civil Resistance Works](https://www.ericachenoweth.com/research/wcrw) by [Erica Chenoweth](https://www.ericachenoweth.com/) and Maria J. Stephan. The authors demonstrated that nonviolent campaigns are generally more effective in achieving their goals compared to violent ones. They also introduced the notable 3.5% rule: no government has withstood a challenge from 3.5% of its population during a peak event.

To explore these findings, we use the [NAVCO 1.2 Dataset](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/0UZOTX) (Nonviolent and Violent Campaigns and Outcomes).

Additionally, we incorporate data from the [Polity Project](https://www.systemicpeace.org/polityproject.html), available through the [Integrated Network for Societal Conflict Research (INSCR)](https://www.systemicpeace.org/inscrdata.html), to capture the regime authority spectrum of each campaign of the dataset.

We utilize `matplotlib` to visualize the findings of the exploratory data analysis, regarding 

- Violent and Nonviolent Campaigns by Decade
- Nonviolent Campaigns and Percentage of Success per Decade
- Success Rate for Violent and Nonviolent Campaigns by Decade
- Largest Resistance Campaigns, 1946-2014

Also, we implement statistical analysis, using `statsmodels` library, in order to examine the effect of multiple factors such as population, participation and membership per capita and the regime type in the probability of success.
Furthermore, we use confidence intervals, in order to derive Chenoweth's 3.5% rule and identify the percentage of participation which gives an indication of a 99% probability of success in the campaign.

--- 

2nd Assignment for Applied Machine Learning 2024 (DMST, AUEB)

You can find the description of the assignment [here](https://github.com/cfragiadakis/Exploring-Why-Civil-Resistance-Works/blob/main/assignment_description.ipynb).
