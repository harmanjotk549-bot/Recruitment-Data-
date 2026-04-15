# Recruitment Screening Output
# Overview
This project provides an automated recruitment screening system that evaluates candidates based on predefined criteria such as skills, experience, and qualifications.


The output file (recruitment_screening_output.csv) contains the processed results, helping recruiters quickly identify the most suitable candidates.

# Project Structure
Recruitment-Screening
│── recruitment_screening_output.csv   # Output dataset
│── README.md                          # Project documentation

# Dataset Description
The dataset contains candidate screening results where each row represents a candidate.

# Key Columns
Candidate_ID → Unique ID of candidate
Name → Candidate name
Skills → Relevant skills
Experience → Years of experience
Education → Qualification details
Score → Calculated screening score
Status → Final result (Selected / Rejected / Shortlisted)

# How It Works
Collect candidate data
Apply screening criteria (skills, experience, etc.)
Generate a score for each candidate


# Classify candidates into categories:
Selected
Shortlisted
Rejected


# Technologies Used
Python 
Pandas 


# CSV Data Handling
Getting Started
1️⃣ Clone the Repository
git clone https://github.com/your-username/recruitment-screening.git
cd recruitment-screening
2️⃣ Install Dependencies
pip install pandas
3️⃣ Run the Code
import pandas as pd

df = pd.read_csv("recruitment_screening_output.csv")
print(df.head())

# Use Cases
Automated resume screening
HR analytics
Candidate shortlisting
Decision support systems

# Disclaimer
This system is designed for assistance only, not final hiring decisions
Ensure data privacy and ethical use of candidate information

# Contributing
Contributions are welcome! Feel free to fork the repo and submit a pull request.

# Future Improvements
Add ML-based prediction model 
Improve scoring algorithm
Build a web interface

# Acknowledgment
This project demonstrates how automation can simplify and enhance recruitment processes.
