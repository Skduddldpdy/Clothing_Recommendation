# Seasonal Outfit Recommender

This project is a seasonal outfit recommendation system that uses Hugging Face open-source tools to analyze user input and suggest the most suitable outfits based on the season and personal preferences.

---

## Features

- Provides outfit recommendations for **spring**, **summer**, **autumn**, and **winter**.
- Leverages Hugging Face models for natural language processing tasks.
- Computes sentence similarity to match user input with predefined outfit options.

---

## Technologies Used

### Hugging Face Transformers
1. **Sentence Transformers**  
   - Model: `all-MiniLM-L6-v2`  
   - Used to compute sentence embeddings and find the most relevant outfit by calculating similarity scores.

2. **BERT Text Classification**  
   - Model: `bert-base-uncased`  
   - Used to analyze and classify user input for additional insights.

---

## How to Run

1. Install dependencies:
   ```bash
   pip install sentence-transformers transformers
