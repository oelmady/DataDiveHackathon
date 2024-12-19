# DataDive Hackathon

Our workflow:

Graphics for Global Poverty
1. Correlations between poverty and key factors like electricity, infrastructure, water, and sanitation.
2. Graphing the key factors globally
3. Clustering by country
Nation level inequality analysis
1. Geo data time series e.g. Gini over time

## Datasets
Besides using the `wbgapi` for referencing datasets, we collected CSVs of the relevant data to simplify analyses.
Future efforts will involve using additional data: more granual regional metrics, more years for samples, and additional factors to consider like education.

### World Bank Global Income Inequality 1988-2002
https://datacatalog.worldbank.org/search/dataset/0047368/Global-Income-Inequality-1988-2002
https://microdata.worldbank.org/index.php/catalog/1784

Lists income percentile distributions (10th through 90th percentile buckets) per country per year for 1988-2002.

### Gapminder Datasets
gapminder-prefixed datasets contain longitudinal per-country, per-year statistics on:
- GNI per capita
- Life expectancy
- Population
