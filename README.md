This project was a team effort where I got to work with these awesome people:

Duncan Wang<br> 
[![GitHub Badge](https://img.shields.io/badge/GitHub-Profile-informational?style=flat&logo=github&logoColor=white&color=0D76A8)](https://github.com/duncan-wang)

Sophie Courtemanche-Martel<br>
[![GitHub Badge](https://img.shields.io/badge/GitHub-Profile-informational?style=flat&logo=github&logoColor=white&color=0D76A8)](https://github.com/scmartel)

Jake Hogan<br>
[![GitHub Badge](https://img.shields.io/badge/GitHub-Profile-informational?style=flat&logo=github&logoColor=white&color=0D76A8)](https://github.com/hoganj15)

<br> 

# Jobster

## Objective:

Nowadays, landing your dream job can be more difficult than ever. Companies are increasingly relying on automated technologies to process prospective applicants, and with the rise of Applicant Tracking Systems (ATS) which filter and rank applicants by their fit to a job posting, it is estimated that 75% of resumes never even reach the hands of a recruiter. The objective of this project is to simplify the application process for job seekers, help them identify which jobs to target, and to increase their chances of bypassing ATS systems and landing their ideal role.

To do so, our project will allow a job seeker to input their resume and a target industry or role, and perform the following:

Match users to postings they are most qualified for based on the similarity scoring between their resume and a job description
Use topic modeling (LDA) to identify key "themes", representing requirements or ideal traits an industry or role is looking for, and use similarity scoring to assess a user's fit to top requirements in that industry or role.
Use Inverse-Document Frequency to cluster jobs together to present a condensed view of what an industry looks like, and present what the top requirements of each cluster of companies is.

## Contents (ipynb):
1. Preprocessing - grab job descriptions
2. Preprocessing - grab resumes
3. Preprocessing - cleaning, tokenization, lemmatization, etc.
4. Task 1. Top jobs for user: Similarity scoring

<p align="center"><img src="https://github.com/AlfonsoCabello/Jobster/blob/main/task1_jobster.PNG" style="max-width:100%;"></p>

5. Task 2: User fit-to industry or job: Topic modeling using LDA

<p align="center"><img src="https://github.com/AlfonsoCabello/Jobster/blob/main/task2_jobster.PNG" style="max-width:100%;"></p>

6. Demo
7. Clustering
8. Limitations

  -Cost of web scraping tools (i.e. SerpAPI)
  -Blockers on LinkedIn 
  -Time to scrape
  -Ability to scrape complex pages
  -Measuring importance of “buzzwords” in various industries

9. Improvements

  -Increasing scope of stopwords to include words which aren’t very useful on a resume (i.e. “hard-working”)
  -Multiple resume formats (Word, PDF)
  -LARAM vs LDA
  -LDAvis embedded and interpreted reports automation for further user insights 
