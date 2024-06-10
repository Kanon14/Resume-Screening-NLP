# Resume-Screening-NLP

## Overview
The ATS Resume Expert is a Streamlit-based web application designed to help HR professionals and job seekers understand how well a resume matches a job description. It utilizes an Applicant Tracking System (ATS) powered by Google's Generative AI to analyze resumes and provide feedback. The app can evaluate the match percentage between the resume and job description, highlight missing keywords, and provide insights into the candidate's strengths and weaknesses.

## Features
- **Upload Resume:** Users can upload their resume in PDF format.
- **Input Job Description:** Users can input the job description against which the resume will be evaluated.
- **Resume Evaluation:** The application evaluates the resume based on the job description provided and returns a detailed analysis.
- **Match Percentage:** The app calculates and displays the percentage match between the resume and the job description.
- **Strengths and Weaknesses:** Provides insights into the candidate's strengths and weaknesses relative to the job description.

## Project Setup
### Prerequisites
- Python 3.9+
- Anaconda or Miniconda installed on your machine.

### Installation
1. Clone the repository:
```bash
git clone https://github.com/Kanon14/Resume-Screening-NLP.git
cd Resume-Screening-NLP
```

2. Create and activate a Conda environment:
```bash
conda create -n nlpenv python=3.10 -y
conda activate nlpenv
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

## How to Run
```bash
streamlit run app.py
```

## Troubleshooting
If facing poppler issue, at the CLI:
```bash
conda install -c conda-forge poppler
```