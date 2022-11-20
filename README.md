# COVID-19 Cases and Unemployment Insurance Claims by State

This Assigment contains the code, final dataset, and source data files for an analysis exploring the relationship between COVID-19 cases and unemployment insurance claims by state. I used the dataset to create a series of interactive Tableau dashboards exploring which states are experiencing the most severe economic fallout from COVID-19, and how that tracks with the states hit hardest by the virus itself.

These dashboards, along with a short accompanying piece, were published by the Georgetown Public Policy Review in April 2020. The link to that publication can be found [here](http://gppreview.com/2020/04/23/covid-19-cases-unemployment-claims-state/).

You can find a brief summary of the files available in this repository below:

* COVID-19.ipynb: Jupyter Notebook containing the code used to compile the dataset
* covid19_unemployment.csv: Final compiled dataset
* Source_Data: Directory containing the three source data files
	* states_daily.csv: Daily data on confirmed COVID-19 cases, by state
		* Source: [The COVID Tracking Project](https://covidtracking.com/api)
	* unemployment_claims.xlsx: Weekly data on unemployment insurance claims, by state
		* Source: [Department of Labor](https://oui.doleta.gov/unemploy/claims.asp)
	* population.xlsx: Yearly data on total population, by state
		* Source: [U.S. Census Bureau](https://www.census.gov/data/tables/time-series/demo/popest/2010s-state-total.html)