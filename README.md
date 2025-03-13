# AI Resume Screening & Candidate Ranking System

## Overview
The AI Resume Screening & Candidate Ranking System is a Streamlit-based web application that allows recruiters to upload multiple resumes in PDF format and automatically rank them based on their relevance to a given job description. This is achieved using Natural Language Processing (NLP) techniques such as TF-IDF vectorization and cosine similarity.

## Features
- Upload multiple resumes in PDF format
- Extract text from resumes
- Input a job description
- Rank resumes based on relevance to the job description
- Display results in a tabular format

![WhatsApp Image 2025-03-13 at 20 14 48_02916d9e](https://github.com/user-attachments/assets/1133c70a-074f-49a3-91eb-463f36773408)

![WhatsApp Image 2025-03-13 at 20 15 25_5bf871fa](https://github.com/user-attachments/assets/cd7068ea-40de-4f32-b551-ec69da9339ed)

## Technologies Used
- Python
- Streamlit
- PyPDF2
- Pandas
- Scikit-learn (TF-IDF Vectorization & Cosine Similarity)

## Installation
### Prerequisites
Ensure you have Python installed on your system. Install the required dependencies using the following command:
```bash
pip install streamlit pypdf2 pandas scikit-learn
```

## How to Run the Application
1. Clone this repository or save the script to your local system.
2. Open a terminal or command prompt and navigate to the script's directory.
3. Run the following command to start the Streamlit app:
```bash
streamlit run app.py
```
4. The application will open in your web browser.

## Usage
1. **Enter Job Description**: Provide a detailed job description in the text area.
2. **Upload Resumes**: Click the file uploader to select multiple resumes in PDF format.
3. **View Ranking**: The application will process the resumes and display a ranked list based on similarity scores.
4. **Interpret Results**: Higher scores indicate a stronger match to the job description.

## How it Works
1. The job description and resume contents are converted into numerical representations using TF-IDF (Term Frequency-Inverse Document Frequency).
2. Cosine similarity is computed between the job description and each resume.
3. The resumes are ranked based on their similarity scores, with the highest-ranked resume being the most relevant.


## Future Enhancements
- Support for parsing structured resume formats.
- Integration with AI-based resume parsing libraries.
- Enhancement using large language models (LLMs) for improved ranking.
