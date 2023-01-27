# Fraud-risk-analysis-ML-DL-project

# AdTracking-Fraud-Detection-ada-boost-kaggle
Fraud risk is everywhere, but for companies that advertise online, click fraud can happen at an overwhelming volume, resulting in misleading click data and wasted money. Ad channels can drive up costs by simply clicking on the ad at a large scale. With over 1 billion smart mobile devices in active use every month, China is the largest mobile market in the world and therefore suffers from huge volumes of fradulent traffic.  TalkingData, China’s largest independent big data service platform, covers over 70% of active mobile devices nationwide. They handle 3 billion clicks per day, of which 90% are potentially fraudulent. Their current approach to prevent click fraud for app developers is to measure the journey of a user’s click across their portfolio, and flag IP addresses who produce lots of clicks, but never end up installing apps. With this information, they've built an IP blacklist and device blacklist.  While successful, they want to always be one step ahead of fraudsters and have turned to the Kaggle community for help in further developing their solution. In their 2nd competition with Kaggle, you’re challenged to build an algorithm that predicts whether a user will download an app after clicking a mobile app ad. To support your modeling, they have provided a generous dataset covering approximately 200 million clicks over 4 days!
The objective of the project is Predicting the probabilities for different click_id's in the test set.** Detecting fraudulent click traffic for mobile app ads.
### Task performed
- uploading the test, train datasets
- cleaning and converting the data types
- separating and combining the data
- feature extractions
- model selection and implementing the best model
- predicting and visualing


### Dataset
The dataset was obtained from here https://www.kaggle.com/c/talkingdata-adtracking-fraud-detection/data.

### File descriptions
train.csv - the training set
train_sample.csv - 100,000 randomly-selected rows of training data, to inspect data before downloading full set
test.csv - the test set
sampleSubmission.csv - a sample submission file in the correct format

UPDATE: test_supplement.csv - This is a larger test set that was unintentionally released at the start of the competition. It is not necessary to use this data, but it is permitted to do so. The official test data is a subset of this data.

### Data fields
Each row of the training data contains a click record, with the following features.
ip: ip address of click.
app: app id for marketing.
device: device type id of user mobile phone (e.g., iphone 6 plus, iphone 7, huawei mate 7, etc.)
os: os version id of user mobile phone
channel: channel id of mobile ad publisher
click_time: timestamp of click (UTC)
attributed_time: if user download the app for after clicking an ad, this is the time of the app download
is_attributed: the target that is to be predicted, indicating the app was downloaded
Note that ip, app, device, os, and channel are encoded.

The test data is similar, with the following differences:

click_id: reference for making predictions
is_attributed: not included

## 🏗️ Built with
![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)


## 👩‍💻 Libraries used
![Pandas](https://img.shields.io/badge/Pandas-2C2D72?style=for-the-badge&logo=pandas&logoColor=purple)
![Numpy](https://img.shields.io/badge/Numpy-777BB4?style=for-the-badge&logo=numpy&logoColor=yellow)
![Matplotlib](https://img.shields.io/badge/Matplotlib-F7931E.svg?style=for-the-badge&logo=Matplotlib&logoColor=orange)
![os](https://img.shields.io/badge/os-F7931E.svg?style=for-the-badge&logo=os&logoColor=green)
![seaborn](https://img.shields.io/badge/Seaborn-2C2D72?style=for-the-badge&logo=Seaborn&logoColor=blue)
![Xgboost](https://img.shields.io/badge/Xgboost-2C2D72?style=for-the-badge&logo=Xgboost&logoColor=blue)


## 📋 Tasks Performed
* 📂 cleaning the data 
* 📂 Feature Extraction
* 📂 constructing model
* 📂 Data Manipulation
* 📂 Data Visualization
* 📂 Interacting with the data in the system with os library


## ✍️ Authors
*HARIRAM


## 🤝 Support
Contributions, issues, and feature requests are welcome!
Give a STAR if you like this project! and FOLLOW do SUPPORT Friends.

