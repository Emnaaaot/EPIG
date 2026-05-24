# EPIG: Emotion-Based Prompting for Personalised Image Generation

Official repository for the paper **"EPIG: Emotion-Based Prompting for Personalised Image Generation"**.

## 📋 Overview

EPIG is a lightweight, training-free method that improves emotional control in text-to-image diffusion models by enriching prompts using psychological valence-arousal dimensions and role-aware decomposition (subject / stimulus / context).

## 📁 Repository Structure
EPIG/
├── notebooks/                  # Google Colab notebooks
│   ├── EPIG_Preprocessing.ipynb
│   ├── llm_expanded_prompts.ipynb
│   └── EvalEPIG_final.ipynb
│
├── data/                       # Required datasets
│   ├── NRC_VAD_with_subject_centric.csv
│   └── llm_expanded_prompts.csv
│
├── results/                    # Generated images
│   ├── standard.zip
│   ├── naive.zip
│   ├── llm_proxy.zip
│   └── epig.zip
│
├── figures/                    # Paper figures
│   ├── qualitative_grid_4x4.png
│   ├── failure_cases.png
│   └── epig-arch.png
│
├── paper/                     
│   └── EPIG_Paper.pdf
│
├── README.md
└── .gitignore
text## 🚀 How to Reproduce

1. Open any notebook in [Google Colab](https://colab.research.google.com)
2. Upload the two CSV files from the `data/` folder when prompted
3. Run the cells

## 📄 Quick Links

- **Full Paper**: [EPIG_Paper.pdf](paper/EPIG_Paper.pdf)
- **Main Evaluation Notebook**: [EvalEPIG_final.ipynb](notebooks/EvalEPIG_final.ipynb)
- **LLM Prompt Expansion**: [llm_expanded_prompts.ipynb](notebooks/llm_expanded_prompts.ipynb)

## 👥 Authors

- **Emna Othmen** — amna.othman@isitc.u-sousse.tn
- Mohamed Yassine Landolsi
- Lotfi Ben Romdhane
