# Lyrics-Based Music Recommendation System 🎵 

[![Python](https://img.shields.io/badge/Python-3.13-blue?logo=python&logoColor=white)](https://www.python.org/)
[![Streamlit](https://img.shields.io/badge/Streamlit-1.44.1-orange?logo=streamlit&logoColor=white)](https://streamlit.io/)

A **content-based music recommender system** that suggests songs based on **lyrics similarity**. Built using **TF-IDF** and **cosine similarity**, this project provides fast, interactive song recommendations through a sleek **Streamlit** interface.  

---

## 🛠️ Technologies Used
- **Python**  
- **Streamlit** – for interactive web app interface  
- **Scikit-learn** – for TF-IDF vectorization and similarity computation  
- **Pandas & NumPy** – for data manipulation  

---

## ⚡ Features
- Content-based recommendations based on **song lyrics**  
- Fast and interactive **web interface** using Streamlit  
- Easily extendable to larger datasets  
- Supports **preprocessing of lyrics** for better similarity results  

---

## 🚀 Getting Started

### Clone the repository and Run
```bash
git clone https://github.com/sruthi-pyda/music-recommendation-system.git
cd music-recommendation-system
pip install -r requirements.txt
cd src
python preprocess.py
python -m streamlit run main.py
```

## 📌 How it Works

- Lyrics from the dataset are preprocessed: tokenized, cleaned, and normalized.
- A TF-IDF matrix is created from the cleaned lyrics.
- Cosine similarity is computed between songs to find similar tracks.
- Users enter a song name, and the system recommends the most similar songs.