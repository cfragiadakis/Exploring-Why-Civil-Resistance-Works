# Exploring Why Civil Resistance Works
This project involves exploratory data analysis (EDA) and statistical analysis using the `statsmodels` library to replicate some of the findings from the influential book [Why Civil Resistance Works](https://www.ericachenoweth.com/research/wcrw) by [Erica Chenoweth](https://www.ericachenoweth.com/) and Maria J. Stephan. The authors demonstrated that nonviolent campaigns are generally more effective in achieving their goals compared to violent ones. They also introduced the notable 3.5% rule: no government has withstood a challenge from 3.5% of its population during a peak event.

To explore these findings, the [NAVCO 1.2 Dataset](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/0UZOTX) (Nonviolent and Violent Campaigns and Outcomes) is used, along with data from the [Polity Project](https://www.systemicpeace.org/polityproject.html), available through the [Integrated Network for Societal Conflict Research (INSCR)](https://www.systemicpeace.org/inscrdata.html), to capture the regime authority spectrum of each campaign of the dataset.

The library `matplotlib` is used to visualize the findings of the exploratory data analysis, focusing on: 

- Visualizing the frequency of nonviolent and violent campaigns per decade
- Highlighting the success rates of nonviolent campaigns across different decades.
- Comparing the success rates of violent and nonviolent campaigns over time.
- Displaying the major resistance campaigns with at least 2.0% population participation, highlighting their final outcomes (successful or not).

Additionally, statistical analysis is implemented to examine the effects of multiple factors—such as population, participation, membership per capita, and regime type—on the probability of success. For each variable, a scatter plot is created to identify potential correlations with the probability of success.

Finally, with the use of confidence intervals, Chenoweth's **3.5%** rule is derived, determining the percentage of participation that indicates a **99%** probability of success in a campaign.

--- 

2nd Assignment for Applied Machine Learning 2024 (DMST, AUEB)

You can find the description of the assignment [here](https://github.com/cfragiadakis/Exploring-Why-Civil-Resistance-Works/blob/main/assignment_description.ipynb).
