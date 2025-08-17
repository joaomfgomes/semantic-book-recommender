# 📚 Semantic Book Recommender with LLMs  

This repository contains all the code for the [freeCodeCamp course](https://www.freecodecamp.org/), **“Build a Semantic Book Recommender with LLMs – Full Course.”**  

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
```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Create a `.env` file in the root directory and add your **OpenAI API key**:

   ```
   OPENAI_API_KEY=your_api_key_here
   ```

4. Download the dataset from Kaggle (instructions in the repo).

5. Run the Gradio app:

   ```bash
   python gradio-dashboard.py
   ```

---

## 📸 Screenshots

Here’s what the app looks like in action:

![Data exploration](images/data-exploration.png)
*Exploring the dataset.*

![Vector search](images/vector-search.png)
*Finding similar books with semantic search.*

![Gradio dashboard](images/gradio-dashboard.png)
*Interactive recommender system built with Gradio.*

---

## 🌍 Live Demo

You can also deploy this project online:

* [Hugging Face Spaces](https://huggingface.co/spaces) (best for Gradio apps ✅)
* [Streamlit Cloud](https://streamlit.io/cloud)
* [Render](https://render.com) / [Railway](https://railway.app)

---

## 📖 License

MIT License – free to use, modify, and share.

---
