# 🌙 SoulPrint AI — Personalized Emotional Text Generator

SoulPrint AI is a unique Machine Learning project that generates text based on **your personal memories and emotional experiences**.  
It does not use any public dataset — the training data comes only from the user.  
So the model output is **impossible to replicate by anyone else**, making this project truly one-of-one.

---

## 🔥 Key Idea

You provide 15–30 memories + the emotions you associate with them.  
The model learns your emotional writing style and then generates text when you input a mood, such as:

> "lonely but hopeful"  
> "missing someone"  
> "calm evening"  

This makes the output feel **authentic, emotional, and deeply personal**.

---

## 🧠 Technologies Used

| Technology | Purpose |
|----------|---------|
| Python | Core development |
| Google Colab | Model training environment |
| Hugging Face Transformers (GPT-2) | Text generation model |
| SentenceTransformers | Emotional memory embeddings |
| Pandas | Data handling |

---

## 📂 Project Structure

SoulPrint-AI/
│
├── data/
│ └── memories.csv # your personal memory dataset
│
├── models/
│ └── soulprint_model/ # trained GPT-2 model files
│
├── demo/
│ └── generate.py # script to test the model
│
└── notebooks/
└── soulprint_training.ipynb # training notebook
