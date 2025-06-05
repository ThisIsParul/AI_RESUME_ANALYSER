
# AI Resume Analyzer 🧠📄

AI Resume Analyzer is a Streamlit-based web application that leverages Natural Language Processing (NLP) to analyze resumes. It extracts essential information from resumes, evaluates their content, and provides smart recommendations to enhance them.

## 🌟 Features

- 📄 Resume Parsing using NLP
- 🧠 Skill Detection and Recommendations
- 🎯 Career Path Suggestions (Data Science, Web Dev, Android, iOS, UI/UX)
- 📈 Resume Scoring based on content structure
- 🎥 Resume & Interview Tips (Video Recommendations)
- 🗺️ Geo-location data capture
- 💬 Feedback Module
- 📊 Admin Dashboard for user analytics

## 🛠️ Built With

- [Streamlit](https://streamlit.io/) - Web Interface
- [PyResparser](https://github.com/bhaviksingh2001/pyresparser) - Resume Parsing
- [Pandas, NLTK, Geopy, PDFMiner] - Backend processing

## 📁 Project Structure

```
├── App.py                   # Main Streamlit Application
├── Courses.py               # Course recommendation data
├── Logo/                    # App logo and branding
├── Uploaded_Resumes/        # Directory to save uploaded resumes
├── requirements.txt         # Python package dependencies
```

## ⚙️ How to Run

1. Clone the repository:
```bash
git clone https://github.com/yourusername/ai-resume-analyzer.git
cd ai-resume-analyzer
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Run the application:
```bash
streamlit run App.py
```

## 🔐 Admin Access

To access the admin panel:

- **Username:** `admin`
- **Password:** `admin@resume-analyzer`

## 📬 Feedback

Users can submit their feedback and rate the application. Admins can view all feedback and visualize it through pie charts.

## 👨‍💻 Developer

Built with ❤️ by [Deepak Padhi](https://dnoobnerd.netlify.app/)

---
