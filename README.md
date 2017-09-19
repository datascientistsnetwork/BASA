# BASA

Data Dictionary
---
1. load sas7bdat dataset into pandas dataframe: 

    pd.read_sas() 

2. find out how many missing values and non-missing values in each field


Field| # of Missings | # of Non-Missing Values | Total Records | % Missing
---|---|---|---|---
Airfield |                             0 | 9984687 | 9984687 | 0%
S2     |                               0 | 9984687 | 9984687|0%
Wait_Time  |                     4534097 | 5450590 | 9984687|45.41%
C_Start     |                    5396421 | 4588266 | 9984687|54.05%
C0           |                   1192532 | 8792155 | 9984687|11.94%
C_avg         |                  5396421 | 4588266 | 9984687|54.05%
Sch_Departure  |                  192231 | 9792456 | 9984687|1.93%
Act_Departure   |                 192231 | 9792456 |9984687|1.93%
BFO_Dest_City    |                125571 | 9859116 |9984687|1.26%
BFO_Destination_Country_Code |    125571 | 9859116 |9984687|1.26%
order                         |        0 | 9984687 |9984687|0.00%
Pass_ID                        |     477 | 9984210 |9984687|0.00%
Departure_Date                  | 192231 | 9792456 |9984687|1.93%
Departure_Time        |           192231 | 9792456 |9984687|1.93%
Time_of_Day            |               0 | 9984687 |9984687|0.00%
Period_of_Week          |              0 | 9984687 |9984687|0.00%
Day_of_Week              |             0 | 9984687 |9984687|0.00%
Month                     |            0 | 9984687 |9984687|0.00%
Season                     |           0 | 9984687 |9984687|0.00%
Year                        |     192231 | 9792456 |9984687|1.93%

