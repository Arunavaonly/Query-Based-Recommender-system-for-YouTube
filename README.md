# Query-Based-Recommender-system-for-YouTube
Query based recommender system for YouTube which focuses on both user engagement as well as quality

# YouTube Video Recommendation System  
**Enhancing recommendations through clickbait detection and dynamic quality-aware ranking**  

---

## 📌 Project Overview  
This repository hosts a research-driven YouTube Video Recommendation System designed to improve user experience by **filtering clickbait content** and prioritizing high-quality videos through a **weighted ranking algorithm**. Unlike traditional popularity-driven systems, this framework integrates:  
- **Clickbait detection** (text, image, and thumbnail-caption disparity analysis).  
- **Dynamic weight adjustment** for features like likes/views ratio, sentiment scores, and comment strength.  
- **Transparent candidate generation** using the YouTube Data API.  

Built for academic research, this project addresses challenges such as misinformation, algorithmic bias, and content homogenization.  

---

## ✨ Key Features  
1. **Clickbait Filtering Module**  
   - **Text Classification**: NLP model to detect sensational titles/descriptions.  
   - **Image Classification**: CNN-based analysis of thumbnails.  
2. **Candidate Generation**  
   - Fetches 50 candidate videos using the YouTube Data API.  
3. **Weightage-Based Ranking Algorithm**  
   - Adjusts weights dynamically based on feature relevance (e.g., likes/views ratio).  
   - Ranks videos using a hybrid score combining engagement and quality metrics.  
4. **Top 5 Recommendations**  
   - Outputs refined, diverse, and trustworthy video suggestions.  

---
