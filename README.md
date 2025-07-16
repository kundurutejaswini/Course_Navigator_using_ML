# Course_Navigator_using_ML

Welcome to **Course Navigator**, an intelligent and personalized course recommendation platform designed to help students navigate the overwhelming sea of online courses and technologies. Built using machine learning and modern web technologies, it recommends tailored courses based on a user’s interests, academic background, and career aspirations.

## 📘 Project Description

In today’s fast-paced educational world, learners face a major challenge: **information overload**. There are thousands of online courses available on platforms like Coursera, Udemy, etc. Without guidance, selecting the most relevant one becomes a struggle.

**Course Navigator** solves this by providing:

- 🎯 Personalized course recommendations using ML algorithms
- 📌 Roadmaps (navigators) to guide learners through trending technologies
- 📈 A content-based filtering approach to match courses to user interests and goals
- ✅ Real-time feedback mechanisms for continuous improvement

## ✨ Features

- 👤 User Registration and Authentication (secure login/signup)
- 🔍 Course Recommender Module (based on user input and data)
- 🧭 Learning Path Navigator (step-by-step roadmaps)
- 💬 Feedback Module (users can submit feedback on the app)
- 📊 Dashboard displaying course domains like Data Science, AI, ML, Web Dev, etc.

## 🛠️ Tech Stack

### Frontend:
- HTML, CSS
- [Streamlit](https://streamlit.io/) (for Python-based web UI)

### Backend:
- Python
- SQLite (User and Feedback Databases)

### Machine Learning:
- `scikit-learn` for vectorization and similarity matching
- Content-Based Filtering using cosine similarity

---

## 📁 Project Structure

course-navigator/
├── app/ # Streamlit app files (Home, Recommender, Navigator, Feedback)
├── data/ # Dataset of courses (CSV)
├── db/ # SQLite databases for users and feedback
├── navigator_pages/ # HTML pages for domain-specific roadmaps
├── static/ # Images and icons
├── README.md # You're here!
└── requirements.txt # Required Python packages


## 🚀 Installation Guide

### Prerequisites
- Python 3.8 or above
- pip
- Streamlit
- SQLite3

### Clone the Repo

```bash
git clone https://github.com/yourusername/course-navigator.git
cd course-navigator
Install Dependencies

pip install -r requirements.txt
Run the App

streamlit run main.py
Navigate to http://localhost:8501 in your browser to use the app.

🧠 How It Works
Recommendation Module:
Uses CountVectorizer to encode course titles.

Applies cosine similarity to recommend top-N similar courses.

Navigator Module:
Provides step-by-step domain roadmaps in web pages (HTML).

Covers areas like: Web Dev, Python, ML, VLSI, Cloud, Networking, Embedded Systems, etc.

Feedback:
Users submit feedback (stored in SQLite).

Admins can use this to monitor and improve user experience.

🧪 Testing
Black Box Testing:
Tested user registration, login validation, course search, and output display.

White Box Testing:
Evaluated backend logic, user authentication, and recommendation accuracy.

🔮 Future Enhancements
Integrate API from real platforms (e.g., Coursera, Udemy)

Add collaborative filtering and hybrid recommender models

Deploy using Docker and make accessible on the cloud

Enable user profile dashboard and course progress tracking
