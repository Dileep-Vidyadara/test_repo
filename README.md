# Covid19 Project based on America Data End2End
* The main objective of this project is to use raw data to perform **ETL** (Extract, Transform and Load) using  **Azure Data Factory**.

### Types of files and data used in the project are listed below:

File Name | Description of File
-------- | ---------
1.population_by_age.tsv.gz (EuroStat/Blob) | This is a zipped file that contains the population data of countries.
2.cases_deaths.csv (ECDC) | This csv contains the number emerging Covid Cases and Deaths followed by the each day.
3.hospital_admissions.csv (ECDC) | This csv file contains the Daily Hospital Admissions, Daily ICU admissions, Weekly Hospital Admissions per 100k, Weekly ICU Admissions per 100k.
4.testing.csv (ECDC) | This csv file contains the emerging covid cases, tests being done, testing_rate and covid postive_rate on the weekly basis.
5.lookups (Blob) | Other miscellaneous  files like Calendar Lookup/dim and Country lookup/dim files used.
