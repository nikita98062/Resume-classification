
# Resume Classification Project 📄

## Overview 👀
This project classifies resumes into different job categories using machine learning.

## Features ⭐
- Upload multiple resumes (PDF/DOCX) 📂
- Extract skills automatically 🔍
- Classify resumes by job profile 🎯
- Filter results by job category 🔄

## Installation 🛠️
```bash
pip install -r requirements.txt
python -m spacy download en_core_web_sm
```

## Usage 📝
1. Run the application:
```bash
streamlit run app.py
```
2. Upload resumes through the interface
3. View classifications and extracted skills
4. Filter results by job category

## Project Structure 📂
```
├── app.py              # Main application code
├── modelDT.pkl         # Trained model
├── vector.pkl          # Vectorizer
├── skills.csv          # Skills database
└── requirements.txt    # Dependencies
```

## Dependencies 📦
- Python 3.8+ 🐍
- Streamlit 🎈
- spaCy 🔧
- NLTK 📚
- PyPDF2 📄
- docx2txt 📝
- pandas 🐼

## Contributing 🤝
Please read our contributing guidelines before submitting pull requests.

## License 📜
This project is licensed under the MIT License.
```