# Kosovo COVID-19 Dataset
Complete COVID-19 data for Kosovo. The aim of this project is having a machine readable dataset for municipalities COVID-19 data in Kosovo.

## Daily reports
This folder contains daily case reports.

### File naming convention
MM-DD-YYYY.csv in UTC.

### Field description
- **Komuna:** Municipality name.
- **Last_Update:** MM/DD/YYYY HH:mm:ss (24 hour format, in UTC).
- **Lat** and **Long:** Dot locations on the dashboard.
- **Confirmed:** Confirmed cases.
- **Deaths:** Confirmed deaths.
- **Recovered:** Confirmed recoveries.
- **Active:** Active cases = total confirmed - total recovered - total deaths.
- **Case_Fatality:** Ratio (%): = confirmed cases per 100,000 persons.

### Update frequency
According to the daily report of IKSHPK.

### Data sources
Instituti Kombëtar i Shëndetësisë Publike të Kosovës [@IKSHPK](https://www.facebook.com/IKSHPK/)

## Time series summary
This folder contains daily time series summary tables, including confirmed, deaths and recovered. All data is read in from the daily case report. The time series tables are subject to be updated if inaccuracies are identified in our historical data. The daily reports will not be adjusted in these instances to maintain a record of raw data.
