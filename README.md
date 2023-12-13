# How the world can make Uber & Co. treat workers better

Dream earnings some days, poverty wages most others: Ride-hailing drivers in Africa and beyond are beholden to the whims of the apps they work for. Here’s how some countries are starting to protect them better.

*In this repository, you will find the methodology, data and code behind
the story that came out of this analysis.*

Story by [Kira Schacht](https://www.twitter.com/daten_drang), with reporting from [Isaac Kaledzi](https://www.dw.com/en/isaac-kaledzi/person-36290439).

**Read the full article on DW.com:** [Link](https://www.dw.com/a-66784838)


## Dataset

The file `Database.xslx` contains the data our analysis is based on. For further information about its structure please refer to the `Metadata` sheet in the file.


## Data sources

### Statista Consumer Insights

Statista regularly runs market research on various segments. We used their data on people who "used ride sharing/hailing services or booked taxis online" during 2022. It is based on online surveys among people aged 18-64 years.

During the survey, the question was phrased as follows: "Which of these ride sharing / ride hailing or online taxi providers have you used in the past 12 months?" Multiple answers were possible.

**Datasets used:**

- [Australia](https://www.statista.com/forecasts/1187910/ride-sharing-hailing-online-taxi-usage-by-brand-in-australia?locale=en)
- [Brazil](https://www.statista.com/forecasts/1226614/ride-sharing-hailing-online-taxi-usage-by-brand-in-brazil?locale=en)
- [China](https://www.statista.com/forecasts/1348307/ride-sharing-hailing-online-taxi-usage-by-brand-in-china?locale=en)
- [Germany](https://www.statista.com/forecasts/998848/ride-sharing-hailing-online-taxi-usage-by-brand-in-germany?locale=en)
- [India](https://www.statista.com/forecasts/1348438/ride-sharing-hailing-online-taxi-usage-by-brand-in-india?locale=en)
- [Mexico](https://www.statista.com/forecasts/1347847/ride-sharing-hailing-online-taxi-usage-by-brand-in-mexico?locale=en)
- [South Africa](https://www.statista.com/forecasts/1371152/ride-sharing-hailing-online-taxi-usage-by-brand-in-south-africa)
- [South Korea](https://www.statista.com/forecasts/1371492/ride-sharing-hailing-online-taxi-usage-by-brand-in-south-korea)
- [United States](https://www.statista.com/forecasts/997157/ride-sharing-hailing-online-taxi-usage-by-brand-in-the-us)

Data might have been updated in the time since our analysis.


### ILO World Employment and Social Outlook 2021

Data on the average earnings of driver-partners comes from a survey run by the International Labour Organization (ILO) for their [World Employment and Social Outlook 2021: The role of digital labour platforms in transforming the world of work](https://www.ilo.org/global/research/global-reports/weso/2021/WCMS_771749/lang--en/index.htm).

In 2019 and 2020, The ILO surveyed 2077 app-based taxi drivers in nine countries (Chile, Ghana, India, Indonesia, Kenya, Lebanon, Mexico, Morocco, Ukraine), asking, among other things, about average earnings before any deductions (e.g. platform commissions, fuel expenses etc.).

### ILO Global Wage Report

To compare drivers' earnings to the average wages of all employees in the respective country, we used 2019 figures from the ILO's [Global Wage Report](https://www.ilo.org/digitalguides/en-gb/story/globalwagereport2022-23).

### World Bank

Since the average earnings of drivers were reported in US Dollar, but the average employee wages in local currency, we used the World Bank [official 2019 annual average exchange rates](https://data.worldbank.org/indicator/PA.NUS.FCRF) to convert the average employee wages to USD as well.

This allowed us to, for instance, calculate how many hours a driver would theoretically have to work each day of the month to reach an average employee income in the respective country.

### Leeds Index of Platform Labour Protest

To analyze the issues drivers and similar platform workers are most concerned about, we used the [Leeds Index of Platform Labour Protest](https://digit-research.org/publication/a-global-analysis-of-worker-protest-in-digital-labour-platforms/), compiled by researchers from The Digital Futures at Work Centre (a collaboration by the universities Sussex and Leeds) and the Centre for Employment Relations Innovation and Change (CERIC) at Leeds University.

The researchers collected a database of platform worker protest events from online news media reports and other online sources. Between January 2017 and July 2020, they identified 1,271 instances of worker protest in the sectors ride-hailing, food delivery, courier services and grocery delivery.

## Interviews

- [Uma Rani](https://glu.iversity.org/en/profiles/uma-rani), Senior Economist, ILO Research Department
- Richard Gbewornyo, Uber driver in Accra, Ghana