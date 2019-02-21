# Decision-Support-System

## Abstract of the Research paper used

### Paper can be found at [Decision-Support-System](https://www.sciencedirect.com/science/article/pii/S0167923615002006)
Predicting the performance of online consumer reviews: A sentiment mining approach to big data analytics

Although online consumer reviews (OCRs) have helped consumers to know about the strengths and weaknesses of different products and find the ones that best suit their needs, they introduce a challenge for businesses to analyze them because of their volume, variety, velocity and veracity. This research investigates the predictors of readership and helpfulness of OCR using a sentiment mining approach for big data analytics. Our findings show that reviews with higher levels of positive sentiment in the title receive more readerships. Sentimental reviews with neutral polarity in the text are also perceived to be more helpful. The length and longevity of a review positively influence both its readership and helpfulness. Because the current methods used for sorting OCR may bias both their readership and helpfulness, the approach used in this study can be adopted by online vendors to develop scalable automated systems for sorting and classification of big OCR data which will benefit both vendors and consumers.


## Running the project

### Ubuntu

```
virtualenv -p python3 venv
source venv/bin/activate
pip install -r requirements.txt
jupyter notebook code.ipynb
```

### Windows
```
virtualenv venv
source venv\Scripts\activate
pip install -r requirements.txt
jupyter notebook code.ipynb
```