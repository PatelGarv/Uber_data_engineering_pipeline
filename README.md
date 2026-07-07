# NYC Uber Data Analytics | Modern Data Engineering GCP Project

## Introduction
So I put this together to actually work with Uber trip data hands-on rather 
than just reading about data engineering. I used Python to handle the logic, 
threw the data into GCP — Cloud Storage, Compute Engine, BigQuery — and 
visualized everything through Looker Studio. Mage handled the pipeline 
orchestration, which honestly made the whole ETL process way cleaner.

---

Mage AI — pipeline orchestration
https://www.mage.ai/
https://github.com/mage-ai/mage-ai

---

##Dataset

NYC TLC trip records — yellow and green taxi data straight from the city. 
Every row logs a trip: when it started, when it ended, where both happened, 
total distance, the full fare breakdown, rate category, payment method, and 
passenger count. Pretty detailed stuff once you start digging into it.

https://storage.googleapis.com/ny-uber-datapipline-2025/uber_data.csv

---

## Data Source

TLC publishes this publicly if you want to explore beyond what's here:
https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page

Column-by-column breakdown lives here:
https://www.nyc.gov/assets/tlc/downloads/pdf/data_dictionary_trip_records_yellow.pdf
