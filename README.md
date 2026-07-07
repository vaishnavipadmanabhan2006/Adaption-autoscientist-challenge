Chest X-Ray Pneumonia Detection — Healthcare AI Model
Adaption AutoScientist Challenge · Category: Healthcare · HackIndia Track

A fine-tuned instruction model trained on chest X-ray pneumonia labels that measurably beats the Healthcare baseline on Adaption's held-out test set — released openly on Hugging Face and Kaggle with full reproducibility.

What I Built
An AI model trained to detect and classify pneumonia from chest X-ray diagnostic labels. The model learns from real medical data to assist healthcare workers in faster and more accurate pneumonia diagnosis. This directly addresses one of the most critical healthcare challenges — delayed or missed pneumonia diagnosis which affects millions of patients globally every year.

Problem It Solves
Pneumonia is one of the leading causes of death worldwide
Manual chest X-ray reading is slow and prone to human error
Rural and understaffed hospitals lack expert radiologists
Early detection saves lives — AI can bridge this gap
How I Built It
Step	Tool Used
Dataset sourced	Kaggle Chest X-Ray Pneumonia Dataset
Data adapted	Adaption Labs Adaptive Data Platform
Model trained	Adaption AutoScientist Loop
Languages	242 languages supported via Adaption
Released	Hugging Face + Kaggle
Links
🤗 Hugging Face dataset: https://huggingface.co/datasets/vaishnavipadmanabhan/adaption-chest-xray-pneumonia-labels
📊 Kaggle dataset: https://www.kaggle.com/datasets/vaishnavipadmanabhan/adaption-chest-xray-pneumonia-labels
🔗 Adaption AutoScientist run: Coming soon
🌐 Live demo: Coming soon
💼 LinkedIn post: Coming soon
🐦 X post (tag @adaption_ai): Coming soon
Repo Layout
adaption-autoscientist-healthcare/
├── README.md                  # This file
├── PROBLEM_STATEMENT.md       # Crisp problem statement
├── MODEL_CARD.md              # HF/Kaggle model card
├── DATASET_CARD.md            # Dataset card (sourcing, cleaning, licensing)
├── SUBMISSION_CHECKLIST.md    # Every step required for prize eligibility
├── SOCIAL_POSTS.md            # LinkedIn and X posts
├── data/                      # Dataset build scripts and notes
├── training/                  # AutoScientist recipe and configs
└── eval/                      # Baseline vs ours evaluation methodology
Reproduce in One Read
data/ — how the chest X-ray pneumonia dataset was sourced, cleaned, and adapted
training/ — the exact AutoScientist recipe and configs used to fine-tune
eval/ — how we score against Adaption's baseline on the held-out test set
Team -INTELLEX
Vaishnavi P S — HackIndia · Adaption AutoScientist Challenge (Healthcare Track)

