# Source code for: ALFRED

![image](https://github.com/user-attachments/assets/817f9ad3-8bfe-4d9e-8685-a2e057b3ced2)

We have provided the implementation of our proposed model ALFRED along with sample data 

* The meme labels and ocr text can be found at data/train_sample.csv

* The meme images can be found at data/sample_memes

* We have precomputed the emotion features fe associated with each meme which can be found at data/sample_emotion_features

## Intructions for viewing the annotation csv file

Due to the presence of newline character in OCR text, conventional word processing software might not be able to parse the file properly
This file is best viewed by loading it as a dataframe using pandas

## Steps to run code

```python
pip3 install -r requirements.txt
python3 main.py
```
