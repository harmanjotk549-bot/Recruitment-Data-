# Recruitment Screening Output

Project Overview

This project focuses on building an automated recruitment screening system that evaluates candidates based on predefined criteria such as skills, experience, and qualifications.

The system generates a structured output file (recruitment_screening_output.csv) that helps recruiters quickly identify the most suitable candidates, improving efficiency and decision-making in the hiring process.

Objectives

Automate the candidate screening process
Reduce manual effort in resume evaluation
Provide data-driven candidate ranking
Improve accuracy and consistency in hiring

Output File Description
File Name: recruitment_screening_output.csv
Format: CSV
Content: Processed candidate screening results

Each record represents a candidate evaluated by the system.

Dataset Structure

Typical columns included in the file:

Candidate_ID – Unique identifier
Name – Candidate’s name
Skills – Relevant skills of the candidate
Experience – Years of experience
Education – Qualification details
Score – Computed screening score
Status – Final decision (Selected / Rejected / Shortlisted)

Working of the System
Input candidate data is collected
Screening criteria are applied:
Skill matching
Experience filtering
Qualification checks
A score is calculated for each candidate
Candidates are categorized based on score thresholds

Key Features
Automated scoring system
Fast candidate filtering
Easy-to-analyze output format
Scalable for large datasets

How to Use
Using Excel / Google Sheets
Open the CSV file directly
Apply filters or sorting for analysis
Using Python
import pandas as pd

df = pd.read_csv("recruitment_screening_output.csv")
print(df.head())

Limitations
Results depend on predefined rules/logic
May not capture soft skills or cultural fit
Requires clean and accurate input data

Future Improvements
Integration with AI/ML models
Resume parsing using NLP
Real-time candidate scoring
Dashboard visualization


Conclusion
The Recruitment Screening System streamlines the hiring process by automating candidate evaluation and providing structured insights, making recruitment faster, more efficient, and data-driven
