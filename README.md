# 📚 Semantic Book Recommender with LLMs  

This repository contains all the code for the [freeCodeCamp course](https://www.freecodecamp.org/),  
**“Build a Semantic Book Recommender with LLMs – Full Course.”**  

The project walks you through building a semantic recommendation system step by step.  

---

## 🚀 Features  

1. **Data Cleaning**  
   - Preprocess and explore book text data.  
   - Code: `data-exploration.ipynb`  

2. **Semantic Search**  
   - Build a vector database to find books similar to natural language queries.  
   - Example: *“a book about a person seeking revenge.”*  
   - Code: `vector-search.ipynb`  

3. **Text Classification**  
   - Use zero-shot LLMs to classify books (e.g., *fiction* vs *non-fiction*).  
   - Code: `text-classification.ipynb`  

4. **Sentiment & Emotion Analysis**  
   - Extract emotions/tones to sort books by *suspenseful, joyful, sad*, etc.  
   - Code: `sentiment-analysis.ipynb`  

5. **Interactive Web App (Gradio)**  
   - User-friendly dashboard for book recommendations.  
   - Code: `gradio-dashboard.py`  

---

## ⚙️ Tech Stack  

- **Python 3.11**  
- **Libraries:**  
  `kagglehub`, `pandas`, `matplotlib`, `seaborn`,  
  `python-dotenv`, `langchain-community`, `langchain-opencv`,  
  `langchain-chroma`, `transformers`, `gradio`, `notebook`, `ipywidgets`  

📌 All dependencies are listed in **`requirements.txt`**  

---

## 🔑 Setup  

1. Clone the repo:  
   ```bash
   git clone https://github.com/your-username/semantic-book-recommender.git
   cd semantic-book-recommender
