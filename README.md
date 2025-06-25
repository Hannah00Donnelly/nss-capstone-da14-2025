## nss-capstone-da14-2025

**Data Dwellers: Finding a Home Through Analytics**

This capstone project evaluates the most suitable U.S. city for relocation among **Raleigh, Seattle, Philadelphia, and Austin**. The analysis focuses on:

- **Transportation**
- **Diversity**
- **Affordability**

By integrating public data, the project aims to balance personal well-being with professional flexibility, while identifying diverse communities.

## Technologies Used:

- Python (Pandas, Matplotlib, Seaborn)
- Excel
- Google Sheets
- Google Slides
- Power BI

## Setup Instructions

1. Clone the repository.
2. Download the required datasets listed below and place them in the `data/` folder.
	- For city specific data '../data/"city name"/' in lower case
	- Example: '../data/austin/file_name.csv'
3. To run this project, you need some Python packages. 
 - Required Imports:
	- import pandas as pd
	- import numpy as np
	- import matplotlib.pyplot as plt
	- import seaborn as sns
	- from adjustText import adjust_text

## Analysis Questions:

- How much each city spends on public transit
- Availability of public transit systems
- Average Commute time
- Racial diversity per city
- Foreign-born population
- Number of languages spoken
- Median monthly rent
- Median home price
- Average monthly utility and internet costs

## Data Sources:

City Budgets for transportation calculations:
- Austin:
	- https://data.austintexas.gov/d/g5k8-8sud
	- 'austin_program_budget_operating_budget_vs_expense_raw_data_20250519.csv'
- Philadelphia:
	- https://opendataphilly.org/datasets/city-operating-budget/
	- operating_budget_fy_2019.csv
- Raleigh:
	- https://arcg.is/18Hjui1
	- 'raleigh_adopted_expense_budget.csv'
- Seattle:
	- https://data.seattle.gov/d/8u2j-imqx
	- 'city_of_seattle_operating_budget_20250518.csv'

- Transportation:
	- https://www.transit.dot.gov/ntd/data-product/monthly-modal-time-series-safety-and-service
	- 'monthly_modal_time_series_transportation_all.csv'

Transit Systems for Each City:
- Philly: SEPTA (Southeastern Pennsylvania Transportation Authority)
- Seattle: King County Metro (King County) and Sound Transit (Central Puget Sound Regional Transit Authority)
- Raleigh: City of Raleigh (GoRaleigh) & Wake County (GoTriangle)
- Austin: CapMetro (Capital Metropolitan Transportation Authority)

Commute Time and Means of Transportation Data:
- Census Commuting Characteristics by Sex S0801
- https://data.census.gov/table?q=S0801

Austin:
- 'austin_travel_time.csv'
- 'austin_means_transport.csv'

Philly:
- 'philadelphia_travel_time.csv'
- 'philadelphia_means_transport.csv'

Raleigh:
- 'raleigh_travel_time.csv'
- 'raleigh_means_transport.csv'

Seattle:
- 'seattle_travel_time.csv'
- 'seattle_means_transport.csv'

Diversity or Social Characteristics:
- Census Social Characteristics DP02
- https://data.census.gov/table?q=DP02
- This includes: place of birth, languages spoken at home, and region of birth of foreign population
- Census data on ancestry appears to be biased towards European countries

Austin:
- 'austin_ancestry.csv'
- 'austin_language.csv'
- 'austin_place_birth.csv'
- 'austin_region.csv'

Philly:
- 'philadelphia_ancestry.csv'
- 'philadelphia_language.csv'
- 'philadelphia_place_birth.csv'
- 'philadelphia_region.csv'

Raleigh:
- 'raleigh_ancestry.csv'
- 'raleigh_language.csv'
- 'raleigh_place_birth.csv'
- 'raleigh_region.csv'

Seattle:
- 'seattle_ancestry.csv'
- 'seattle_language.csv'
- 'seattle_place_birth.csv'
- 'seattle_region_birth.csv'

Cost of Living Data:
- This includes average monthly rent, home prices, utility costs, and personal consumption expenditures
- Personal Consumption Expenditures by State:
- https://www.bea.gov/news/2024/real-personal-consumption-expenditures-state-and-real-personal-income-state-and
- 'personal_consumption_expenditures_all_bea_2023_pc.csv'
- Residential average monthly bill by Census Division, and State:
- https://www.eia.gov/electricity/sales_revenue_price/
- 'eia_avg_monthly_utility_all.csv'
- https://worldpopulationreview.com/state-rankings/water-prices-by-state
- 'water-prices-by-state-2025.csv'

Housing Data:
- https://www.zillow.com/research/data/
- 'metro_mean_sale_price_all.csv'
- 'metro_mean_rent_all.csv'

City Counties:
- Seattle: King County
- Philadelphia: Philadelphia
- Austin: Travis County
- Raleigh: Wake County

## Key Terms:
- UZA: urbanized area
- Per Capita Personal Consumption Expenditures: the average amount of money each person spends on goods and services annually 

## Capstone Proposal:
- https://docs.google.com/document/d/1jEov03OxxdwJZkL75jja9udKg1Vqd_331WfJm8YlBKU/edit?tab=t.0#heading=h.uyvrgle8xdgu

## Final Presentation: 

Google Slides:
- https://docs.google.com/presentation/d/1mnav6ejLHY0YiMRgrxLAyHYXTZLaRHhrcbJGlDrDJPs/edit?usp=sharing

Charts for Google Slide:
- https://docs.google.com/spreadsheets/d/19h8UskpRaXuDodfEGB1lDgAi2k6vWtZMrHy_tLmKSoU/edit?usp=sharing

## Interactive Dashboard:
- https://tinyurl.com/datadwellershdonnelly
- https://app.powerbi.com/view?r=eyJrIjoiNjUzYjRmNWMtMDMxZC00NmY0LWIzOTgtMWE5NzZkMjhjYzI4IiwidCI6IjEwMWRhNTg3LTE4NDMtNGY1Mi04YjhhLTE3YjA2OWM2NmQzMyIsImMiOjJ9&embedImagePlaceholder=true

## Color Reference

| Color                         | Hex         |
| ------------------------------|------------ |
| Austin  or Texas              |#d29d6c      |
| Raleigh or North Carolina     |#bbc7ba      |
| Seattle  or Washington    	|#856d89      |
| Philadelphia or Pennsylvania  |#9e6076      |
| Drove Themselves		|#f2a291      |
| Public transportation		|#dbb6b5      |
| Worked from home		|#f8e3dc      |
| Other Means			|#90a3b4      |
|Service Area Population Density|#5fc1e9      |
|UZA Population Density		|#556070      |
|Geographic Coverage		|#fbca94      |
|Population Coverage            |#eb7065      |

