# MelodicVision 🎵
### Music Genre Classification via Fine-Tuned ResNet-18 on Mel Spectrograms

## 📌 Overview
MelodicVision is an end-to-end deep learning pipeline for automatic music genre classification. Instead of processing raw audio directly, each 30-second audio clip is converted into a 128×128 Mel spectrogram image, transforming the problem into a 2D image classification task. A ResNet-18 CNN pretrained on ImageNet is then fine-tuned on these spectrogram images using discriminative layer-wise learning rates.

## 🎯 Results
| Metric | Value |
|--------|-------|
| Overall Test Accuracy | 82% |
| Best Epoch | 12 |
| Training Samples | 799 |
| Test Samples | 200 |

## 🎼 Genres
Blues · Classical · Country · Disco · Hip-Hop · Jazz · Metal · Pop · Reggae · Rock

## 🛠️ Tech Stack
- Python, PyTorch, torchvision
- librosa (audio processing)
- ResNet-18 (transfer learning)
- Grad-CAM (explainability)
- GTZAN Dataset

## 📂 Dataset
GTZAN — 1,000 audio clips (30s each) across 10 genres  
👉 https://www.kaggle.com/datasets/andradaolteanu/gtzan-dataset-music-genre-classification

## 🚀 How to Run
1. Clone the repo
2. Install dependencies: `pip install torch torchvision librosa matplotlib seaborn scikit-learn`
3. Fill in your Kaggle credentials in the notebook (cell: *Write Kaggle API credentials*)
4. Run the notebook: `melodicvision.ipynb`

## 📄 Paper
Published at **ICONET26** — International Conference on Intelligent Computing and Next-Generation Technologies  
Beirut Arab University, Debbieh, Lebanon — October 2026

## 👤 Author
**Mohammad Salhab**  
Department of Computer Engineering, Beirut Arab University  
GitHub: [@MohammadSalhabEngineer](https://github.com/MohammadSalhabEngineer)
