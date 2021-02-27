# UI_datathon_2021

Team 46's repo for UIUC 2021 datathon

Members: Roger Qiu, Rong Wang, Quanyu Zuo, Tongshu Liu

### Prereq

```
pip3 install --user -r requirements.txt
```

### File Struct

 - preprocessing.ipynb: Jupyter notebook that contains code for preprocessing data from the raw
        data provided. Feature engineering happens here.

 - analysis.ipynb: main notebook that carries out the statistical learning. It takes in the data
        produced by preprocessing.ipynb, does some additional preprocessing, run the KMeans
        algorithm, then performs some evaluation.

 - visualilzation.ipynb: a helper visualization notebook that helps explore how different features
        distinguishes data points.
