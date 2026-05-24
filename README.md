# LLM for Materials Discovery

AI-assisted molecular structure generation using Large Language Models and DFT optimization.

## Overview
This project investigates whether LLMs can generate molecular structures usable as initial guesses for DFT calculations.

The generated structures are compared to PubChem reference structures using:
- RMSD
- Success rate
- HOMO-LUMO gap differences
- Energy differences after DFT optimization

## Models Used
- Gemini 2.5 Flash
- GPT-5.4
- Claude Sonnet 4.5
- DeepSeek V3.1
- LLaMA 3.3 70B
- Mistral Large

## Tools & Libraries
- Python
- ASE
- GPAW
- RDKit
- Streamlit
- NumPy
- Matplotlib

## Workflow
1. Generate molecular structures using LLMs
2. Convert structures to `.xyz`
3. Compare with PubChem references
4. Align structures using Kabsch/Hungarian methods
5. Run DFT optimization
6. Compare electronic and structural properties

## Thesis
Bachelor project by Kristoffer T. Nielsen & Valdemar A. Olsen.
