# CMPE-255 Data Mining


## Setup

### Install Anaconda
https://www.anaconda.com

### Configure PyCharm to use base Anaconda interpreter

### Install dependencies to convert notebooks to PDF
```bash
conda install conda-forge::nbconvert-webpdf
playwright install chromium
```

## Convert notebooks to PDF
```bash
jupyter nbconvert --to webpdf 26-01-28/assignment1.ipynb
```
