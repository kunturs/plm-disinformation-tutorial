# Pretrained Language Models for Disinformation Detection — Tutorials

Hands-on notebooks for clickbait detection with pretrained language models.
Click a badge to open the notebook in Google Colab, then run the cells from top to bottom.

| Notebook | What you learn | Runtime | Open |
|---|---|---|---|
| 01 · Embedding baseline | TF-IDF vs frozen multilingual embeddings, 5-fold CV, error analysis | CPU | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kunturs/plm-disinformation-tutorial/blob/main/01_embedding_baseline.ipynb) |
| 02 · Fine-tune a transformer | XLM-R with the Hugging Face Trainer, test set, zero-shot on Indonesian | T4 GPU | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kunturs/plm-disinformation-tutorial/blob/main/02_finetune_transformer.ipynb) |
| 03 · Cross-lingual transfer | Train on English, test on Indonesian, re-tune the decision threshold | CPU | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kunturs/plm-disinformation-tutorial/blob/main/03_cross_lingual_transfer.ipynb) |

**For notebook 02:** in Colab choose *Runtime → Change runtime type → T4 GPU*.
**To keep your work:** *File → Save a copy in Drive*.

## Datasets
- Chakraborty, A., Paranjape, B., Kakarla, S., & Ganguly, N. (2016). *Stop Clickbait: Detecting and Preventing Clickbaits in Online News Media.* ASONAM. Hugging Face: `marksverdhei/clickbait_title_classification` (MIT).
- William, A., & Sari, Y. (2020). *CLICK-ID: A novel dataset for Indonesian clickbait headlines.* Data in Brief, 32, 106231. Hugging Face (MTEB copy): `mteb/IndonesianIdClickbaitClassification` (CC-BY-4.0).

## Author
Soveatin Kuntur — Faculty of Mathematics and Information Science, Warsaw University of Technology
