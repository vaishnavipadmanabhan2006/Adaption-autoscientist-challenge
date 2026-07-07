# Dataset Card — Chest X-Ray Pneumonia Labels

## Dataset Details

| Field | Details |
|---|---|
| Dataset Name | adaption-chest-xray-pneumonia-labels |
| Created by | Vaishnavi P S |
| Track | Healthcare |
| License | CC0: Public Domain |
| Language | English + 242 languages |
| Format | Instruction dataset (prompt + completion) |

---

## Links

- 🤗 Hugging Face: https://huggingface.co/datasets/vaishnavipadmanabhan/adaption-chest-xray-pneumonia-labels
- 📊 Kaggle: https://www.kaggle.com/datasets/vaishnavipadmanabhan/adaption-chest-xray-pneumonia-labels

---

## What This Dataset Contains

A cleaned and adapted instruction dataset built for training AI models to detect pneumonia from chest X-ray diagnostic labels. The dataset contains prompt and completion pairs that teach the model to classify pneumonia cases accurately.

### Columns

| Column | Description |
|---|---|
| prompt | Patient symptoms, X-ray findings, clinical notes |
| completion | Diagnosis classification and clinical guidance |

---

## How This Dataset Was Built

### Step 1 — Sourcing
- Primary data sourced from chest X-ray pneumonia datasets on Kaggle
- Supplementary medical instruction data added for diversity
- All data is publicly available and anonymized

### Step 2 — Cleaning
- Removed duplicate entries
- Standardized column names and formats
- Removed incomplete or corrupted rows
- Validated medical terminology accuracy

### Step 3 — Adapting
- Uploaded to Adaption Labs Adaptive Data Platform
- Converted to instruction format with prompt and completion pairs
- Expanded to 242 languages using Adaption translation feature
- Quality evaluated and improved through Adaption pipeline

### Step 4 — Publishing
- Published on Kaggle as public dataset
- Mirrored on Hugging Face for model training access
- Full documentation included

---

## Intended Use

- Training AI models for pneumonia detection
- Healthcare AI research
- Medical education and training tools
- Baseline comparison for healthcare models

---

## Limitations

- Based on labeled X-ray data, not raw images
- May not cover all pneumonia subtypes equally
- Should not be used as sole basis for clinical decisions
