# Pandas Data Analysis 

Jupyter Notebook file that uses Pandas to analyze district-wide standardized test results.

## Description

This repository is designed to analyze data and create summary tables of standardized math and reading test scores. The data is stored in two CSV files (schools_complete.csv, students_complete.csv) in the Resources directoy of the PyCitySchools directory. 

The CSV files are imported into the Jupyter Notebook file (PyCitySchools_starter.ipynb) and merged using a left join. From the merged dataframe, mathematical functions (i.e., sum, length, average, percent) are used to created a **District Summary** table, and the GroupBy function is used to create a similar table, **School Summary**, which displays the same information for each school in the district.

Data Analysis:
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
* Navitage to the home directory and open index.html in your browser.

### Data Sources

* Hulcr J, Latimer AM, Henley JB, Rountree NR, Fierer N, et al. (2012) A Jungle in There: Bacteria in Belly Buttons are Highly Diverse, but Predictable. PLoS ONE 7(11): e47712. doi:10.1371/journal.pone.0047712 [Access Data](http://robdunnlab.com/projects/belly-button-biodiversity/results-and-data/)


## Authors

Katlin Bowman, PhD

E: klbowman@ucsc.edu

[LinkedIn](https://www.linkedin.com/in/katlin-bowman/)
