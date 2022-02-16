# Time Series Anomaly Detection of The Official DKI Jakarta Covid-19 Daily Cases
English | Indonesian

## Background
As of July 18, 2021, the Covid-19 (Corona Virus Disease 2019) pandemic has hit Indonesia for 16 months since the Indonesian government announced the discovery of the first two cases of Covid-19 on March 2, 2020. Since then, various efforts have been made by the government. central and local governments to suppress the spread and fatality of Covid-19. The DKI Jakarta Provincial Government has repeatedly implemented Large-Scale Social Restrictions (PSBB), starting from three phases of strict PSBB, transitional PSBB, Implementation of Micro Community Activity Restrictions (PPKM), until finally the government centrally pulled the emergency brake with the Java-Bali Emergency PPKM policy in July 3, 2021.

However, until July 19, 2021, DKI Jakarta became the highest contributor of confirmed cases with 727,010 cases or 26.1% of 2,877,476 cases in Indonesia and became the province with the highest active positive cases in Indonesia, which was 112,957 cases. Using a dataset obtained from the official website of the DKI Jakarta Provincial Government Covid-19 monitoring corona.jakarta.go.id, we conducted an analysis of the detection of simple outliers (anomalies) in the spread of Covid-19 cases in DKI Jakarta. We use the 'Daily Positive' variable in the 'Data Jakarta' section of the dataset to detect outliers.

Dataset: tiny.cc/Datacovidjakarta

## Methods

- Univariate Analysis
- Naive Outliers Detection with Z-Score
- Naive Outliers Detection with Interquartile Range (IQR)
- Anomaly Detection with ARIMA
- Power Transformation
- Yeo-Johnson Transformation
- Dynamic Thresholding for Anomaly Detection and Handling

## References
JAKARTA HEALTHY, SAFE. Jakarta's COVID-19 Response Team. (n.d.). https://corona.jakarta.go.id/en.
