# Arms Imports Per Country (1950-2020)

![](https://www.googleapis.com/download/storage/v1/b/kaggle-user-content/o/inbox%2F12064410%2F950e5066d0365c77abe8192aaaec8c72%2Fglobal%20arms%20imports%20flag.png?generation=1677862750498500&alt=media)

# 25,933 DAYS (January 1st, 1950 to December 31st, 2020)
This is a dataset that tracks **arms imports** of various countries, regions and select groups worldwide from 1950 to 2020. 

All data are official figures from the Stockholm International Peace Research Institute that have been compiled and structured by myself. The arms imports data of *selected groups* such as anti-Castro rebels are also being tracked in order to increase the analytical potential of the dataset. Please note that a '0' indicates that the **value of deliveries is less than 0.5m**, and a null value indicates that the **value of deliveries are too minimal** to be counted. A weapon that has been in service in another armed force is given a **value of 40%** of that of a new weapon, while an used weapon that has been significantly refurbished or modified by the supplier before delivery is given a **value of 66%** of that of a new weapon.

Why did I create this dataset? The **arms trade** continues to be a **significant issue** in the world today and contributes to **instability in third-world countries**. By uploading *time-series data* regarding arms imports per country over the past seven decades, I hope that the community is able to determine the various statistical trends offered. In my personal opinion, achieving a **quantitative yet objective viewpoint** of a subject such as the arms trade is crucial to understanding the underlying issues that plague our world.

# Data Sources
##### The primary data source used was the official website of the Stockholm International Peace Research Institute (SIPRI), which publishes data pertaining to global conflicts. An independent international institute, the SIPRI pursues extensive research into armaments, arms control and disarmament worldwide. Considering the SIPRI's role as one of the most respected think tanks around the globe, no other institute is more equipped to provide insight into arms imports.

1. [The Stockholm International Peace Research Institute's Arms Trade Importer/Exporter TIV Tables](https://www.bls.gov/web/laus.supp.toc.htm) - The Stockholm International Peace Research Institute has published arms imports and exports data since 1950. Only the imports data was used for the dataset as its implications are far more meaningful than exports, an area where first-world countries such as the USA would predictably dominate.
2. [The Stockholm International Peace Research Institute's Sources and Methods](https://www.sipri.org/databases/armstransfers/sources-and-methods) - The Stockholm International Peace Research Institute released a detailed overview of their arms imports data, the methodology behind their data, and the proper definitions and terminologies for the variables tracked. The guide mainly provided essential contextual knowledge needed to create a meaningful dataset.

# Statistics Being Tracked
- Country/Region/Group (Name)
- Year (Total arms imports, in millions, for each year from 1950 to 2020)

# Dataset History
2023-03-03 - Dataset is created (26,725 days after temporal coverage start date).

[Kaggle Dataset](https://www.kaggle.com/datasets/justin2028/arms-imports-per-country) - The same data but on Kaggle.

# Code Starter
[Link to Notebook](https://www.kaggle.com/code/justin2028/arms-imports-per-country-1950-2020-code-starter/notebook)
