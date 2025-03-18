# ResumeMaster: AI-Driven Resume Analyzer

ResumeMaster is an AI-powered application designed to parse and analyze resumes using natural language processing (NLP). It extracts keywords, categorizes them into relevant sectors, and offers recommendations, predictions, and analytics to applicants based on keyword matching.

## Features

- **Resume Parsing:** Extracts structured data from resumes for detailed analysis.
- **Keyword Clustering:** Identifies and groups keywords into relevant sectors.
- **Recommendations:** Provides suggestions and predictions to enhance resume quality.
- **Analytics:** Offers insights based on keyword matching to improve job application success.

## Tech Stack

- **Frontend:** Streamlit, HTML, CSS, JavaScript
- **Backend:** Python (Streamlit)
- **Database:** MySQL
- **Modules:** pandas, pyresparser, pdfminer3, Plotly, NLTK

## Scope

- **Data Structuring:** Converts resume data into structured formats for organizational analytics.
- **User Improvement:** Assists users in refining their resumes through feedback and recommendations.
- **Educational Insights:** Enables educational institutions to assess student resumes before placements.
- **Continuous Enhancement:** Gathers user feedback for ongoing tool improvement.

## Screenshots

### 1. Admin:
- **Main Screen:**
![Main Screen](screenshots/admin/1-main-screen.png)

- **User Data:**
![User Data](screenshots/admin/2-user-data.png)

- **User DataCSV:**
![User DataCSV](screenshots/admin/3-user-datacsv.png)

- **Feed Data:**
![Feed Data](screenshots/admin/4-feed-data.png)

- **Pie Experienced Level:**
![Pie Experienced Level](screenshots/admin/5-pieexp.png)

- **Pie Resume Score:**
![Pie Resume Score](screenshots/admin/6-piescre.jpg)

- **Pie Location:**
![Pie Location](screenshots/admin/7-pielocation.png)

### 2. Feedback:
- **Form:**
![Form](screenshots/feedback/1-form.png)

- **Analytics:**
![Analytics](screenshots/feedback/2-analytics.png)

### 3. User:
- **Main Screen:**
![Main Screen](screenshots/user/1-main-screen.png)

- **Analysis:**
![Analysis](screenshots/user/2-analysis.jpg)

- **Skills Recommendation:**
![Skills Recommendation](screenshots/user/3-recom.png)

- **Course Recommendation:**
![Course Recommendation](screenshots/user/4-recom.png)

- **Resume Score:**
![Resume Score](screenshots/user/5-tipsscore.png)

- **Video Tips:**
![Video Tips](screenshots/user/6-recom.png)

## Installation & Setup

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/ResumeMaster.git

cd ResumeMaster
```

## 2. Install Dependencies
```bash
pip install -r requirements.txt
```

## 3. Run the Application
```bash
streamlit run app.py
```

## License

This project is licensed under the MIT License.
