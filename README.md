# AI-Cyber-Projects

---

##  1. AI Multimedia System: Movie Genre & Audio Summary Generator, FILMCEPTION

**Objective:**  
To create an interactive system that predicts movie genres and converts summaries into audio across multiple languages.

###  Key Functionalities
- **Genre Prediction:**
  - Trained on [CMU Movie Summary Dataset](https://www.kaggle.com/datasets/msafi04/movies-genre-dataset-cmu-movie-summary)
  - Multi-label classification using models like Logistic Regression or BERT
- **Audio Summary Conversion:**
  - Translate summaries into **Arabic**, **Urdu**, and **Korean**
  - Convert translated text into speech using tools like gTTS or pyttsx3
- **NLP Preprocessing:**
  - Cleaning, tokenization, lemmatization, and metadata extraction
- **Interactive Menu-Driven Interface:**
  - Input a summary → Choose audio conversion or genre prediction → Output result accordingly

---

##  Tech Stack

- **Languages:** Python
- **Libraries:** Scikit-learn, Hugging Face Transformers, gTTS, Pyttsx3, Pandas, NLTK, TTS APIs
- **ML/NLP Tools:** BERT, SBERT, T5, DistilBART, TF-IDF, Word2Vec

---

##  How to Run

1. Clone this repo  
   `git clone https://https://github.com/Bakhtawar12384/AI-Filmception-Project

2. Set up environment (recommend using `venv` or `conda`)

3. Run the corresponding scripts from:
   - `vare/` → For vulnerability assessment
   - `movie-ai/` → For genre prediction and audio summary
