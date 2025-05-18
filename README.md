# Smart Flashcard Backend (Take-Home Assignment)

This is a simple backend service for a smart flashcard app. It allows users to add flashcards with just a question and answer — the subject is automatically inferred using a rule-based NLP method.

## 🔧 Features

- Automatically classifies flashcards by subject (e.g., Physics, Biology, Math)
- API to add flashcards (`POST /flashcard`)
- API to retrieve flashcards from mixed subjects (`GET /get-subject`)
- Stores data locally using SQLite
- Built using Flask in a Jupyter Notebook for easy testing

## 🛠️ Installation

```bash
git clone https://github.com/your-username/smart-flashcard-backend.git
cd smart-flashcard-backend
pip install -r requirements.txt


