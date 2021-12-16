# Pandas Data Analysis 

Jupyter Notebook file that uses Pandas to analyze district-wide standardized test results.

## Description

This repository is designed to analyze data and create summary tables of standardized math and reading test scores. The data is stored in two CSV files (schools_complete.csv, students_complete.csv) in the Resources directoy of the PyCitySchools directory. 

The CSV files are imported into a Jupyter Notebook file (PyCitySchools_starter.ipynb) and merged using a left join. From the merged dataframe, mathematical functions (i.e., sum, length, average, percent) are used to created a **District Summary** table, and the GroupBy function is used to create a similar table, **School Summary** (shown below), which displays the same information for each school in the district.
<p align="center">
  <img src="https://user-images.githubusercontent.com/74067302/146276913-e3a78524-ad4d-47d8-8891-517b912600bb.png" alt="Summary Table"/>
</p>

### Data Analysis
- The sort_values function is used to list the top 5 and bottom 5 schools by overall % of students that passed both math and rading.
- The GroupBy function is used to create tables that show average and % passing math and reading scores by grade, school size, spending, and school type (i.e., district or charter).

### Analysis Results
  * The overall passing rate decreased as with increased spending per student.
  * Small (<1,000 students) and medium (1,000-2,000 students) sized schools had higher overall passing rates than large (2,000-5,000 students) schools.
  * Average math and reading scores were higher for charter schools compared to district schools.

## Getting Started

### Technologies Used 

* Jupyter Notebook
* Python
* Pandas

### Installing

* Clone this repository to your desktop.
* Navigate to the PyCitySchools directory and run the PyCitySchools_starter.ipynb file in Jupyter Notebook. 

### Data Sources

* Mockaroo, LLC. (2021). Realistic Data Generator. https://www.mockaroo.com/

## Author

Katlin Bowman, PhD

E: klbowman@ucsc.edu

[LinkedIn](https://www.linkedin.com/in/katlin-bowman/)
