# Gender Analysis

This project aims at providing a first step on gender analysis of open source developers.

This is expected to be useful for those interested in having data. As data are necessary 
when making decisions, having proper numbers about the status of the gender-gap
is necessary to check if different applied policies are successful within the project.

# Dependencies

* Metrics Grimoire databases. The proposed example is based on the OpenStack databases publicly available in the Activity Board project.
* Genderize.io database info. The link between name and gender is provided by the genderize.io API. This provides probabilities of gender based on the name and, if given, on the country.


# Building a dashboard

* This project also contains scripts to produce specific indexes in Elastic Search that will be later visualized thanks to Kibana. These are not requirements, but will help to have a first glimpse of the data.
* Ipython notebooks are provided as a way to help third parties how the code works and this is a mere example of use.
