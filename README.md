# Python Recycling Classifier

Recycling Classifier is a AI project done during my exchange programme with BrainAI. This programme can classify items whether it can be recycled.

However, this classifier is not so advanced as it can detect things wrongly. For example, an Iphone would be classified as a loud speaker. This is due to the model from OpenVINO (Hello World) that I used which is not advanced enough to read images.

## Prerequisites

- [Anaconda](https://docs.anaconda.com/free/anaconda/install/index.html)
- [Jupyter Notebook & Jupyter Lab](https://jupyter.org/install)

## Setup

- **(base) C:\cd recyclableclassifier** (path link to recyclableclassifier folder)
- **(base) C:\recyclableclassifier>conda create --name recyclableclassifier python=3.11.8 anaconda**
- **(base) C:\recyclableclassifier>conda activate recyclableclassifier**
- **(recyclableclassifier) C:\recyclableclassifier>**
- **(recyclableclassifier) C:\recyclableclassifier>pip install --upgrade --user pip**
- **(recyclableclassifier) C:\recyclableclassifier>pip install tensorflow==2.13.1**
- **(recyclableclassifier) C:\recyclableclassifier>pip install openvino==2024.0.0**
- **(recyclableclassifier) C:\recyclableclassifier>pip install opencv-python==4.9.0.80**
- **(recyclableclassifier) C:\recyclableclassifier>pip install ipywidgets==8.1.2**
- **(recyclableclassifier) C:\recyclableclassifier>pip install gradio**
- **(recyclableclassifier) C:\recyclableclassifier>jupyter lab**

## Classifying steps

1. Click on Recycling_Classifier
2. Open Recycling Classifier.ipynb
3. Restart kernal and run all cells
4. Choose any image from your files (must be in jpeg form)
5. Upload file
6. Click on inference
7. Your result page!
