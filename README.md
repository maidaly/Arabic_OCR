# Arabic_OCR
This repo contains Arabic OCR App. The APP can be used to extract the Arabic text from the images. The is built based on the [EasyOCR](https://github.com/JaidedAI/EasyOCR) library. EsayOCR built  detection/recognition model to detect and recognize the characters and words. For detection part they used the pretrained model for [CRAFT](https://arxiv.org/abs/1904.01941) algorithm. For recognition they built a [CRNN](https://arxiv.org/abs/1507.05717) model. For our case, we used the two pretrained model for Arabic language. To deploy the models we used the [Streamlit](https://www.streamlit.io/) library.

## Installation
There are many option to run or install the app we will show three of them:
### 1. Run via Colab
you can run colab notebook and go through the ngrok link to run the app.<br>
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1JMyzh_fnhTtZnN_hfzMmm3Pr3AON89SK?usp=sharing),<br>
### Install via conda
In this step we assume that conda is preinstalled on the machine. If conda is not installed you can follow the steps on the that [link](https://docs.conda.io/projects/conda/en/latest/user-guide/install/)<br>
1. At first we need to clone the repo to the local machine.
```bash
git clone https://github.com/maidaly/Arabic_OCR.git
```
2. Create a new conda enviroment to run the app inside it.
```bash
conda create --name arabic_ocr
```
then we need to activate the enviroment.
```
conda activate arabic_ocr
```
3. Install the required python packages
```bash
pip install -r requirements.txt
```
