# 🎭 Deploying a Sentiment Analysis Model

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![AWS SageMaker](https://img.shields.io/badge/AWS_SageMaker-FF9900?style=flat&logo=amazon-aws&logoColor=white)

A web application that performs sentiment analysis on movie reviews using a deployed recurrent neural network (RNN) on AWS SageMaker. Part of the **Udacity Deep Learning Nanodegree** program.

## 📖 About

The notebook and Python files provided here result in a simple web app which interacts with a deployed recurrent neural network performing sentiment analysis on movie reviews. This project assumes some familiarity with SageMaker — the mini-project, Sentiment Analysis using XGBoost, should provide enough background.

Please see the [README](https://github.com/udacity/sagemaker-deployment/tree/master/README.md) in the root directory for instructions on setting up a SageMaker notebook and downloading the project files (as well as the other notebooks).

## ✨ Features

- 🧠 **RNN Model** — Recurrent neural network for sentiment classification
- ☁️ **SageMaker Deployment** — Model deployed on AWS SageMaker
- 🌐 **Web Interface** — Simple web app for real-time predictions
- 📓 **Full Pipeline** — Training notebook with end-to-end workflow

## 🛠️ Tech Stack

| Component | Technology |
|-----------|-----------|
| **Model** | PyTorch (RNN) |
| **Deployment** | AWS SageMaker |
| **Frontend** | HTML |
| **Training** | Jupyter Notebook |

## 📁 Project Structure

```
├── SageMaker Project.ipynb   # Full training & deployment notebook
├── train/
│   ├── train.py              # Training script
│   ├── model.py              # Model definition
│   └── requirements.txt      # Training dependencies
├── serve/
│   ├── predict.py            # Inference script
│   ├── model.py              # Model for serving
│   ├── utils.py              # Utility functions
│   └── requirements.txt      # Serving dependencies
├── website/
│   └── index.html            # Web interface
└── Web App Diagram.svg       # Architecture diagram
```

## 🚀 Getting Started

1. Set up an AWS SageMaker notebook instance
2. Clone this repository
3. Follow the steps in `SageMaker Project.ipynb`

## 👤 Author

**Sanjay Santhanam**

---

⭐ Star this repo if you found it useful!
