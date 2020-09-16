# COVID-19 data from LA County

The plots below display information about COVID-19 cases in LA County, along with thresholds that must be met in order for schools to re-open. The data was obtained from the [New York Times](https://github.com/nytimes/covid-19-data) and is updated automatically every six hours using Github Actions. 

The plot below shows cases per 100,000 in LA County. The horizontal lines correspond to state definitions of "Moderate", "Substantial" and "Widespread" infection. For details see the [California Blueprint for a Safer Economy]](https://covid19.ca.gov/safer-economy/). Schools can reopen for in-person instruction once their county has been in the Substantial (red) tier for at least two weeks.

![image2](plots/classification.png)

Prior to the Blueprint for a Safer Economy, school re-opening thresholds were based on the total cases summed over the prior 14 days (per 100,000). The plot below shows this data, which remains useful because it provides insight into the number of *currently active* COVID-19 infections.

![image1](plots/graph.png)
![image2](plots/classification.png)

This site was developed by Sina Booeshaghi, Ingileif Hallgrimsdottir and Lior Pachter.
