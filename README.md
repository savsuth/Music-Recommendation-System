# 🎵 Music Recommendation System (Lyrics + Metadata + Optional Spotify Audio Features)

Hybrid recommender that combines:
- **Sentence-BERT** lyric embeddings for semantic similarity
- **TF-IDF** over metadata (artist, genre, lyrics) for keyword similarity
- *(Optional)* **Spotify audio features** (tempo, energy, valence, …) for re-ranking

## 🚀 Features
- Natural-language search (e.g., “moody indie for a rainy night”)
- Seed track recommendation (title + year)
- Hybrid scoring: embeddings + metadata
- Optional re-ranking via Spotify audio features

## 📂 Dataset
Use the *Genius Song Lyrics with Language Information* dataset  
(https://www.kaggle.com/datasets/carlosgdcj/genius-song-lyrics-with-language-information)  
Place the CSV at project root as `song_lyrics.csv` (filtered to English, ≥50 chars).

## 🛠️ Setup
```bash
pip install -r requirements.txt
jupyter notebook MusicRecommendationSystem.ipynb



