# How transparent is US influence in EU legislation?
#### This project was created within the scope of the Lede Program 2024, at Columbia Journalism School.
#### [Here](https://konstantinamalt.github.io/us_lobbying_eu/) is the project's website.
#### [Here](https://github.com/konstantinamalt/Lede_Project_01_us_lobbying_eu/blob/main/lobbying/Project_01.ipynb) is the project's analysis and original dataset.

## Project's goal:
#### With this project I wanted to see how many US companies and groups are lobbying the EU, how much money they have spent on lobbying, and which EU files are they targeting, in an attempt to find trends regarding US interests in EU legislation and policies and highlight corporate influence on citizens' lives, while practicing my skills in scraping with BeautifulSoup, data analysis with pandas and scrolly-telling visualisations. However, during the analysis I realised the biggest issue was the lack of transparency regarding US lobbying.

## Findings:
- #### US influence in the EU is more powerful than ever.
- #### US lobbying companies in the EU are increasing by hundreds while the money spent from their activity is increasing by millions. Since 2021, the lobbying costs have risen by 44 % in 2023, while in a four year period from 2017 to 2021, the money spent for lobbying increased only by 8 %. 
- #### Big Tech is lobbying Europe's digital economy, and is the top 10 US lobbyist in the EU for 2023.
- #### Microsoft ramped up its spending by 40 percent since 2022, and is the biggest spender in 2023 alongside Apple, with 7 million euros in lobbying spending each.
- #### Out of the total 314 companies, 149 have declared lobbying costs, that in 20 cases reach up to 1 million euros each, but do not appear to have participated in any meetings. These 149 companies appear to have spent in total at least 61 million euros from 2014-2023.

## Data collection and cleaning (Python, Pandas, BeautifulSoup):
#### 1. Downloaded CSV file with data regarding the names and registration number of the US companies lobbying the EU from the EU Transparency Register.
#### 2. Used python and scraping to collect data for the companies' financial information, by creating the 314 URLs (using the site LobbyFacts as a base url and the registration number of the companies from my original CSV file) to download the CSV files of each company, storing them in a dataframe and merging them together. Data for the meetings was also collected in the same way again from LobbyFacts website.
#### 3. Cleaned the duplicates.

## Data analysis (Pandas and Jupyter Notebook):
#### 1. Money spent by US companies in total yearly
#### 2. Top 10 biggest lobbyists in 2023 and 2022
#### 3. Biggest lobbyists over a decade (2014-2023)
#### 4. Lobbyists with the most meetings over the decade
#### 5. Lobbyists with no meetings, but lobbying costs in the decade
#### 6. DG/PORTFOLIOS that are lobbied the most by US companies each year
#### 7. Meetings by top 10 lobbyists

## Visualisation:
#### Flourish

## Page Template:
[Code written by Jonathan Soma](https://github.com/jsoma/page-templates/blob/main/scrolly-images/index.html).

# File's index:
#### lobby_usa_eu.csv = the original dataset from EU Transparency Register with the names and registration numbers of each company
#### Project_01.ipynb = python code with data collection, cleaning and analysis.

# Success & Failures:
#### 1. Able to find my way around my lack of Selenium knowledge, since the website I wanted to scrape had dynamic content. Although I would love to have learned Selenium for this.
#### 2. Used scraping and a for loop to download, read and and create a big dataset which I had never done before.
#### 3. Able to get 80% of the analysis I wanted. The other 20% was to be able to identify trends regarding the main EU files, but could not structure my df properly for that since there were more than one values in one cell divided by commas.
#### 4. File organisation was not the greatest which created issues while uploading my work on Github..
#### 5. Would love to had the time to create more visualisations.
