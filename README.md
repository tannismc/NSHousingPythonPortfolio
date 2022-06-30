# NSHousingPythonPortfolio
A python project to examine the pre-pandemic housing market in Nova Scotia in order to understand the current housing crisis.

OBJECTIVE
The growing housing crisis in Canada has been making news headlines for almost a year. The cost of buying a house has skyrocketed, rental rates are soaring, and there is low availability of both, leading to increasing numbers of unhoused people. As governments attempt to address the crisis, the question of what Canadians can afford to pay for housing becomes very important, especially in Nova Scotia, where income taxes are among the highest in the country while minimum wage is the lowest. 
This project will examine the housing crisis, comparing incomes to housing costs across the country, and then diving deeper by comparing this to the housing market (i.e. housing supply) in Nova Scotia in particular.

DATA SOURCES
The data sourced for this project comes from two (external) open sources: Statistics Canada and the Canada Mortgage and Housing Corporation (CMHC). Statistics Canada is the Canadian federal government's statistical office. The Canadian Income Survey (CIS) is conducted by Statistics Canada. CMHC is a crown corporation (a government organization structured like an independent company). CMHC is the national housing agency. More information can be found at the organizations' websites: https://www.statcan.gc.ca/en/start and https://www.cmhc-schl.gc.ca/en/about-us. Two datasets were used in the analysis:

Canadian Income Survey, 2018
File Citation: Statistics Canada, 2022, "CIS2018 SPSS sav.zip", Canadian Income Survey, 2018, https://hdl.handle.net/11272.1/AB2/G6T0LC/RAD63D, Abacus Data Network, V1 

Dataset Citation: Statistics Canada, 2022, "Canadian Income Survey, 2018", https://hdl.handle.net/11272.1/AB2/G6T0LC, Abacus Data Network, V1, UNF:6:RlzI4LxHQ+ZRmY8Hn85cuw== [fileUNF] 

Housing Market Indicators for Nova Scotia (time series)
Canada Mortgage and Housing Corporation (CMHC), Housing Market Indicators for Nova Scotia, 1990-2016, accessed on June 16, 2022. This information is reproduced and distributed on an “as is” basis with the permission of CMHC.

A third table was referred to in the final Tableau storyboard:
Statistics Canada Table 11-10-0191-01 Income statistics by economic family type and income source, accessed on June 27, 2022.

The Statistics Canada 2016 Census boundaries shapefile was used for the maps of Canada. A map of Nova Scotia was extracted from the same file. Shapefiles for Canada and Nova Scotia were exported from QGIS with a Statistics Canada Lambert Conformal Conic projection and used as custom background maps in the Tableau Storyboard. The Geopandas library was used in the Python analysis to ensure maps were generated with a Lambert Conformal Conic projection rather than a Mercator Projection (the Mercator projection grossly distorts most of northern Canada). https://www12.statcan.gc.ca/census-recensement/2011/geo/bound-limit/bound-limit-2016-eng.cfm

The final Tableau storyboard does not include all analysis in the Python project. Rather, it explores the underlying cause of the housing crisis and what type of approach is needed to solve it. The Tableau storyboard can be found here: https://public.tableau.com/views/UnderstandingtheNovaScotiaHousingCrisis/UnderstandingTheNovaScotiaHousingCrisis?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link.
