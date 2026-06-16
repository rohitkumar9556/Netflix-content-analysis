

## 🌐 Socials:
[![Instagram](https://img.shields.io/badge/Instagram-%23E4405F.svg?logo=Instagram&logoColor=white)](https://instagram.com/rohitkumarpatra455) [![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://linkedin.com/in/www.linkedin.com/in/rohitkumar9938) [![email](https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white)](mailto:rohitkumarpatra033@gmail.com) 

# 💻 Tech Stack:
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black) ![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white) ![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white) ![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)
# 📊 GitHub Stats:
![](https://github-readme-stats.shion.dev/api?username=rohitkumar9556&theme=dark&hide_border=false&include_all_commits=false&count_private=false)<br/>
![](https://streak-stats.demolab.com/?user=rohitkumar9556&theme=dark&hide_border=false)<br/>
![](https://github-readme-stats.shion.dev/api/top-langs/?username=rohitkumar9556&theme=dark&hide_border=false&include_all_commits=false&count_private=false&layout=compact)

---
[![](https://komarev.com/ghpvc/?username=rohitkumar9556&icon=0&color=6)](https://visitcount.itsvg.in)

<!-- Proudly created with GPRM ( https://gprm.itsvg.in ) -->
---------------------------
# Netflix-content-analysis
---------------------------
## Project Overview
This project analyzes netflix content to get business insights like which genre of movie most watched ,highest or lowest  rated movie  etc.  using Python-based Exploratory Data Analysis (EDA).

####  The analysis focuses on  factors like:

   •highest rated movies

   •lowest rated movies

   •highest vote in avg column

   •highest no. released movies in a year

   •most frequent genre  movie

####  This project demonstrates practical skills in:

  • Data Cleaning
  
  • Exploratory Data Analysis

  • Data Visualizatin
  
  •   Business Insight Generation


<img width="164" height="148" alt="netflix logo" src="https://github.com/user-attachments/assets/b78d80d6-4df5-4905-ba1e-255f6b04c32d" />

## Business Problem

 -netflix movies analysis
 
-highest watched movie genre

-highest rated movie

-lowest rated movie

-most no. of movies released in which year?

This project helps analyze viewers choice on watching movies.

## Technologies Used
  i-Python
  
  ii- Pandas
  
  iii-  NumPy
  
  iv-Matplotlib

  v-seaborn
  
  vi-jupyter notebook

## Dataset Information
The dataset contains netflix movies data related information such as:

**1-** Release_Date

**2-** Title

**3-** Overview

**4-** Popularity

**5-** Vote_Count

**6-** Vote_Average

**7-** Original_Language

**8-** Genre

**9-** Poster_Url

# Project Workflow
## 1. Data Collection
Imported dataset using Pandas
## 2. Data Cleaning

**(i)** Checked missing values

**(ii)** checked duplicate value

**(iii)** checked outlier

**(iv)** split commas and spaces

**(v)** categorization of column

**(vi)** Removed inconsistencies
## 3. Exploratory Data Analysis
**(1)** Distribution Analysis

**(2)** categorical Visualization

**(3)** histogram plot
# Import Libraries
```bash
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
```
# Load Dataset
```bash
df = pd.read_csv(r"C:\Users\Admin\Downloads\mymoviedb.csv", lineterminator='\n')
df.head()
```
# Data Cleaning
```bash
df.isnull().sum()
```
# Project Visualizations
## 1. Age Distribution
<img width="506" height="510" alt="download" src="https://github.com/user-attachments/assets/fd4732a6-9192-4fdd-9b5c-d07512f16a04" />


## Analysis
we can notice from the above visual that Drama genre is the most frequent genre
in our dataset and has appeared more than 14% of the times among 19 other
genres.
## 2.votes distribution

<img width="404" height="405" alt="vote_disribution" src="https://github.com/user-attachments/assets/086988d2-232f-4353-9452-8d6104701490" />

## Analysis 
we can see from the above graph that average category movies get most rating

## Release date distribution
<img width="451" height="345" alt="releasedatedisribution" src="https://github.com/user-attachments/assets/3e3034c4-8e1f-4060-b503-2e9bc9646244" />

# CONCLUSION
### Q1: What is the most frequent genre in the dataset?
Drama genre is the most frequent genre in our dataset and has appeared more than
14% of the times among 19 other genres.
    
### Q2: What genres has highest votes ?
we have 25.5% of our dataset with popular vote (6520 rows). Drama again gets the
highest popularity among fans by being having more than 18.5% of movies popularities.
    
### Q3: What movie got the highest popularity ? what's its genre ?
Spider-Man: No Way Home has the highest popularity rate in our dataset and it hagenres of Action , Adventure and Sience Fiction .
    
### Q4: What movie got the lowest popularity ? what's its genre ?
The united states, thread' has the highest lowest rate in our dataset
and it has genres of music , drama , 'war', 'sci-fi' and history`.
    
### Q5: Which year has the most filmmed movies?
year 2020 has the highest filmming rate in our dataset.








  
