# Indicator-Dashboard
A pythonic way to access and analyze initiative data and to build insightful infographics that convey a snapshot view of a city’s performance. To learn more, click [here](https://github.com/esridc/Indicator-Dashboard/wiki/Indicator-Dashboard-information)

## Motivation
To ease into the process of making data open and working with open data, we have put together a recommended list of key datasets or Indicators that, if provided and configured, can generate dashboards and meaningful analytics.

Hub's Indicators for Governments can be conceptually classified into the following three categories:
   
   * **Measures** are data measured over space and time that indicate trends, outliers and comparisons. Eg. Crime, Street crashes, parking violation
    * **Places** are important locations that support common public service. Eg. Schools, Hospitals, Transit Stops
    * **Boundaries** are distinct areas that denote an administrative, operational, or conceptual limit. Eg. Neighborhoods, Census Tracts, Counties

Categorizing data into these explanatory types helps generalize them to understand and analyze them appropriately.

For instance, a temporal analysis applies to a **Measure**, whereas it is critical to observe how accessible a **Place** is to the areas around it. A **Boundary**, on the other hand, provides a great sub-division to aggregate your Measures/Places against and to notice their effect on demographics. Click [here](https://github.com/esridc/Indicator-Dashboard/blob/master/Python%20dashboards.ipynb) to see an example


## Indicator type and analytics generated


| Indicator |    Attribute    |  Analytic                            |
|-----------|-----------------|--------------------------------------|
|  Measure  |   `time`        | histogram, weekday-weekend pie chart |
|           |  `category1`    | bar chart                            |
|           |  `category2`    | pie chart                            |
|           |                 | heat map                             |
|   Place   |    `value`      | Average count (text statistic)       |
|           |  `category1`    | bar chart                            |
|           |  `category2`    | pie chart                            |
|           |                 | map of locations                     |
|  Boundary |`value1`,`value2`| scatter plot                         |
|           |  `category1`    | pie chart                            |
|           |                 | Map of enriched boundary             |


## Getting started with it:

1. Clone this Github Repository to get a copy of the dashboard scripts we have put together.

2. Customize the notebook by providing the relevant initiative id, sign it to ArcGIS with your credentials and make calls to specific functions such as `measure_dashboard()`, `measure_place()` or `measure_boundary()` based on the particular indicator classification and watch the analytics unfold.

## Want to Contribute?

Make a Pull Rquest to this repository with the changes you propose.

To recommend enhancements or report issues, click [here](https://github.com/esridc/Indicator-Dashboard/issues)
