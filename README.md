# bank_marketing
Personal loans are a lucrative revenue stream for banks.  The typical interest rate of a two-year loan in the United Kingdom is [around 10%](https://www.experian.com/blogs/ask-experian/whats-a-good-interest-rate-for-a-personal-loan/).
## Objective:
The objective of this project is to clean, reformat, and split the data collected by a bank during a recent marketing campaign into three distinct CSV files (client.csv, campaign.csv, and economics.csv). The cleaned data will follow specific formatting and data type requirements so that it can be seamlessly imported into a PostgreSQL database for future analysis. The cleaned data will also support upcoming marketing campaigns aimed at encouraging clients to take personal loans.
## Overall Description:
You are provided with a dataset called "bank_marketing.csv", which contains information about clients, the marketing campaign aimed at encouraging them to take out personal loans, and related economic indicators. The project involves the following key tasks:
### 1.Data Splitting: The initial dataset is split into three tables:
#### >client.csv: Contains personal and demographic information about the bank's clients.
#### >campaign.csv: Contains data related to the current and previous marketing campaigns, including the number of contacts made and the outcomes of these campaigns.
#### >economics.csv: Contains economic data such as the consumer price index and the Euribor three-month rate for each client.
