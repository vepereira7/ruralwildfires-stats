# Rural Wildfires

This project was carried out as part of the statistics course and the main goal was to define a research question that can be addressed by the data available [here](https://web.archive.org/web/20210324213433/http://www2.icnf.pt/portal/florestas/dfci/Resource/doc/estat/list/Lista-Incendios-2015.zip).

## Research Questions
- Q1 - Is there any relationship in between when started the fire and total burnt area in that fire?

- Q2 - Is there a relationship between the action time and the number of burned areas?

- Q3 - Fires with TempoAcao greater than 13 minutes have a AreaTotalQueimada above than 50 acres?

In order to create this variable **(TempoAcao)**, I subtracted **Data Intervencao** and **HoraIntervencao** (which is the date and the time that the firefights start to fight the fire) to **Data** and **HoraAlerta** (which is the date and the time that was given the alert).
