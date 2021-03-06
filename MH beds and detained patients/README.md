# “People shouldn’t have to reach crisis point before they can access the care and support they need”
### An investigation into how available beds, occupancy rates and the ratio of detained to informal patients in mental health inpatient services is affecting patient care and the accessibility of services

The article was published on 26 August 2021 and can be read [here](). 

## Data analysis and visualisation

The story was based on data from different sources. 

**1. Available mental illness beds**

NHS England publishes [data on available mental illness beds](https://www.england.nhs.uk/statistics/statistical-work-areas/bed-availability-and-occupancy/bed-data-overnight/). This includes a time series from 1987. 

The data used in the story can be found [here](https://github.com/vfillis/mental-health-stories/blob/main/MH%20beds%20and%20detained%20patients/bed-availability-and-occupancy.xlsx). 

<img src="data visualisations/bed-availability-England.png" width=70%>

**2. Bed occupancy rates**

Data on the capacity and occupancy of mental health wards in NHS trusts has been obtained through Freedom of Information requests. 

The request has been sent to 50 NHS mental health trusts in England. 40 trusts replied in time and supplied data. 

The data can be found [here](https://github.com/vfillis/mental-health-stories/blob/main/MH%20beds%20and%20detained%20patients/bed-availability-and-occupancy.xlsx). 

<img src="data visualisations/bed-occupancy.png" width=70%>

**3. Detained and informal patients**

Data on the number of detained and informal patients in adult mental health wards in NHS trusts has been obtained through Freedom of Information requests. 

The request has been sent to 50 NHS mental health trusts in England. 35 trusts replied in time and supplied data. 

The data can be found [here](https://github.com/vfillis/mental-health-stories/blob/main/MH%20beds%20and%20detained%20patients/informal-detained-patients.xlsx). 

<img src="data visualisations/detained-informal-patients.png" width=70%>

**4. Referrals to mental health services**

Data on referrals to mental health services is part of the [Mental Health Services Monthly Statistics](https://digital.nhs.uk/data-and-information/publications/statistical/mental-health-services-monthly-statistics/performance-may-provisional-june-2021). 

I downloaded the CSV files from April 2019 to May 2021 (as this was the latest available data) and have merged them using the command line. I then analysed the data in R. The script can be found [here](https://github.com/vfillis/mental-health-stories/blob/main/MH%20beds%20and%20detained%20patients/referrals-MH-services.Rmd). 

The final data can be found [here](https://github.com/vfillis/mental-health-stories/blob/main/MH%20beds%20and%20detained%20patients/MHSDS-referrals-England.xlsx).

<img src="data visualisations/mental-health-referrals.png" width=70%>
