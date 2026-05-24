# EPIG: Emotion-Based Prompting for Personalised Image Generation

Official implementation of the paper **"EPIG: Emotion-Based Prompting for Personalised Image Generation"**.

## Overview

EPIG is a lightweight, training-free method that enhances emotional expressiveness in text-to-image diffusion models (SDXL-Turbo) by enriching prompts using psychological valence-arousal dimensions and role-aware decomposition (subject/stimulus/context).

## Repository Structure
EPIG/
├── code/
│   ├── EPIG_Preprocessing.ipynb          # LLM prompt expansion
│   ├── EvalEPIG_final.ipynb              # Main evaluation + figures
│   └── EPIG_Paper_Final.ipynb            # Clean version (optional)
├── data/
│   ├── NRC_VAD_with_subject_centric.csv
│   └── llm_expanded_prompts.csv
├── results/
│   ├── standard.zip
│   ├── naive.zip
│   ├── llm_proxy.zip
│   └── epig.zip                      # Generated images + metadata
├── figures/
│   ├── qualitative_grid_4x4.png
│   ├── failure_cases.png
│   └── epig-arch.png
├── paper/
│   └── EPIG_Paper.pdf                # Final LaTeX paper
└── README.md
text## Code Availability

The full implementation, data, and generated images are publicly available in this repository.

**Paper**: [EPIG Paper](paper/EPIG_Paper.pdf)

**Main Notebooks**:
- [LLM Prompt Expansion](code/llm_expanded_prompts.ipynb)
- [Main Evaluation](code/EvalEPIG_final.ipynb)

## How to Reproduce

1. Clone the repo:
   ```bash
   git clone https://github.com/Emnaaaot/EPIG.git
   cd EPIG

Upload the required files in Colab:
NRC_VAD_with_subject_centric.csv
llm_expanded_prompts.csv

Run EvalEPIG_final.ipynb

Citation
bibtex@article{othmen2026epig,
  title={EPIG: Emotion-Based Prompting for Personalised Image Generation},
  author={Othmen, Emna and Landolsi, Mohamed Yassine and Ben Romdhane, Lotfi},
  journal={...},
  year={2026}
}
Contact
Emna Othmen — amna.othman@isitc.u-sousse.tn
