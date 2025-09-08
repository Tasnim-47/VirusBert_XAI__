# VirusBERT-XAI: Transformer-based Classification of Highly Pathogenic Viruses with Explainability

This repo contains code and assets for classifying 20 virus types from genome sequences using a BERT-based model (DNABERT) plus XAI (attention, SHAP).

## Features
- 20-class balanced dataset pipeline (FASTA → k-mers)
- Fine-tuning DNABERT for multi-class classification
- Explainability: attention maps, SHAP

## Setup
```bash
git clone <repo-url>
cd virus-bert-xai
pip install -r requirements.txt
