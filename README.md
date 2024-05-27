# NSGROW

Project Contributors: Kanav Bhardwaj (Dalhousie University), Matthew Carl (Dalhousie University), Yakov Fainshtein (Dalhousie University)

This repository has all the required files and data for this project.

Background: Cities, and sub-regions, around the world, serve as hubs of economic activities. The main backbone of 
this urban landscape is efficient and strategic resource allocation. Strategic investments in various amenities and 
careful management of available resources help promote sustainable development, economic growth, 
innovation, and community development, and ensure fiscal sustainability among others. Due to the importance 
of resource allocation, poor or ineffective resource allocation can hinder the development and well-being of an 
urban community. The effects include economic stagnation, social inequalities, environmental degradation, 
educational and health disparities, and an increase in social unrest, just to name a few. Addressing the 
challenges around efficient and strategic resource allocation requires a data-driven approach that can leverage 
insights and different approaches from Municipal Fiscal Statistics to aid decision-making. In this situation, a 
data-driven approach can highlight previous and current trends, patterns, and relationships, which in turn can be 
used to predict and analyze future needs. This will aid policymakers and stakeholders to make informed 
decisions, maximize the impact of strategic investments, promote economic and community development, and 
directly impact environmental sustainability.

Problem Objectives:

The project's core objective is to leverage historical data to develop predictive models for annual regional 
expenditure, focusing on identifying high expenditure sectors and their interrelationships. This involves a 
systematic analysis of historical data across various sectors to detect patterns, trends, and correlations. The 
predictive models will enable precise forecasting of yearly expenditures for specific regions, with a particular 
emphasis on sectors with significant spending. To support municipal decision-making, the project will utilize 
visualizations to elucidate these relationships and expenditure trends. Additionally, it incorporates a continuous 
evaluation mechanism to enhance the predictive tool's accuracy and efficiency over time. This professional 
approach is designed to facilitate strategic planning and resource allocation by providing clear, actionable 
insights into regional spending patterns.

Significance: The significance of our project lies in addressing the critical need for effective resource allocation in 
Nova Scotia's municipalities. These communities depend on strategic budgeting to ensure economic and social 
well-being. Ineffective budget management can lead to economic stagnation, social inequality, and 
environmental issues, which in turn strain healthcare, education, and can escalate social unrest. Municipal 
leaders face the specific challenge of forecasting expenditures without the risk of overspending that could lead 
to fiscal stress and impact service delivery. Our project introduces a predictive tool tailored to the fiscal 
environment of Nova Scotia. It will allow leaders to anticipate yearly expenses, identify potential financial 
risks, and adjust spending to maintain economic stability. This initiative concentrates on data from Nova 
Scotia's counties and contextual economic indicators, aiming to enhance fiscal foresight without delving into 
sector-specific predictions. It's a strategic decision that streamlines focus and maximizes the tool’s 
effectiveness. By improving fiscal planning, this tool is set to bolster municipal service sustainability and 
promote the financial health of Nova Scotia’s communities, making it an essential step towards long-term 
prosperity.

Data Collection and Ownership:

Primary Data Set: 
Our Primary dataset, “Municipal Fiscal Statistics: Operating Fund Total Revenues and Expenditures by 
Regional Municipality”, from the Data Nova Scotia Website, features revenue and expense time-series data for 
Nova Scotia's regional municipalities. Initial analysis revealed that some regions lacked complete data for our 
period of interest, leading us to exclude these due to their minimal size and data. The refined dataset covered 49 
towns and rural municipalities. This prompted us to incorporate external datasets to capture broader fiscal 
influences beyond yearly activities. Discovering more comprehensive data for Nova Scotia's larger counties 
than for smaller municipalities, we consolidated the 49 areas into Nova Scotia’s 18 counties for a more effective 
analysis.

External Data Set #1: Global GDP’s
From Worldbank.org, this dataset details annual GDP growth percentages globally from 1960 to 2022. We 
focused on this dataset to examine its potential as an indicator for predicting Nova Scotia's expenditures. 
Specifically looking at Canada's GDP growth/ decline from 2013 to 2020. 

External Data Set #2: Canadian Inflation Rate
We sourced a dataset from Statista.com, originally compiled from the Bank of Canada's records, containing 
Canada's monthly inflation rates from January 1993 to December 2023. We identified inflation as a valuable 
addition to our study due to its effect on the financial sector. Focusing on the period from 2013 to 2020, we 
calculated the average annual inflation rates to incorporate into our analysis. 

External Data Set #3: Regional Populations, Nova Scotia
From the Government of Canada's website, this dataset provides a comprehensive population breakdown for all 
counties within Nova Scotia from 2001 to 2022. Population plays a direct role in fund allocation thus we knew 
it was pivotal to our project. Our focus was specifically on the populations of all counties between 2013 and 
2020. Moreover, we calculated the year-over-year (YOY) population change for each district, both as a discrete 
value and as a percentage.

External Data Set #4: Land Areas of Targeted Regions
We obtained a dataset from the Government of Canada website to inform our analysis, selecting it for its 
comprehensive coverage of municipal divisions across Canada, based on the 2016 and 2021 national censuses. 
This dataset provided detailed metrics on population, dwelling counts, land areas, and population densities. 

External Data Set #5: County-Wise Average Residential and Commercial Tax Rates
From the Government of Canada's website, this dataset outlines the residential and commercial tax rates for 
each county in Nova Scotia from 2009 to 2024. Tax rates, much like inflation, significantly influence economic 
behavior, affecting how individuals and businesses allocate their finances. Recognizing the importance of 
understanding these dynamics for our analysis, we specifically focused on examining both commercial and 
residential tax rates from 2013 to 2020. 

External Data Set #6: Minimum Wage, Nova Scotia
From the Open Data Nova Scotia website, this dataset provides us information of the minimum wage of the 
province from year 2002 to 2023 from which we specifically considered the data from year 2013 to 2020. 
Minimum Wage influences the fiscal dynamics of the province, making it worthwhile to be examined.
