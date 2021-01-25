# Arabic_OCR
This repo contains Arabic OCR App. The APP can be used to extract the Arabic text from the images. The is built based on the [EasyOCR](https://github.com/JaidedAI/EasyOCR) library. EsayOCR built  detection/recognition model to detect and recognize the characters and words. For detection part they used the pretrained model for [CRAFT](https://arxiv.org/abs/1904.01941) algorithm. For recognition they built a [CRNN](https://arxiv.org/abs/1507.05717) model. For our case, we used the two pretrained model for Arabic language. To deploy the models we used the [Streamlit](https://www.streamlit.io/) library.

## Installation
There are many option to run or install the app we will show three of them:
### 1. Run via Colab
you can run colab notebook and go through the ngrok link to run the app.
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1JMyzh_fnhTtZnN_hfzMmm3Pr3AON89SK?usp=sharing)
### Install via conda
At first we need to clone the repo to the local machine.
,,,bash
