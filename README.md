# COVID Deaths in Spain from the MoM perspective

Doubts have been raised in Spain regarding whether, somehow, the covid-deaths are largely unreported.
This projects aims at assisting in clarifying the issue by comparing the following datasets:
- the reported daily fatalities due to covid,
- the mortality figures due to all causes (MoMo).

A Jupyter notebook is included, together with the dataset at 20200414. 
This dataset has been compiled from official sources:
- https://momo.isciii.es/public/momo/dashboard/momo_dashboard.html#datos
- https://covid19.isciii.es/.

The only manipulation of the datasets corresponds to cleaning excess data as:
- dates beyond the target time frame,
- geographical dissaggregations,
- demographic dissagregations.

The results (at 20200414) show that there is likely an underreporting at the cumulated level:
- 18800 excess deaths over the 99% threshold compared to 18600 reported deaths due to covid.
- 22300 excess deaths over the average compared to 18600 reported deaths due to covid.

This represents an overall underreporting of **15%** at the cumulated level.

![cumulated](https://github.com/Rigonz/covid_excess_deaths_Spain/blob/master/data/20200414_covid_cumulated.png)

There is also likely an under-reporting at the daily level:
- daily reported peak of deaths due to covid: 950
- daily peak of excess deaths over 99% threshold: 1250
- daily peak of excess deaths over average: 1357

This represents a peak underreporting of **24 to 30%** at the daily peak level.

![daiy](https://github.com/Rigonz/covid_excess_deaths_Spain/blob/master/data/20200414_covid_daily.png)
