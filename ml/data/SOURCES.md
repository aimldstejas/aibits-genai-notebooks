# Datasets used by the Machine Learning End To End notebooks

Every dataset is public. The notebooks download what they need automatically in their **Setup** cell:
either from this folder (raw GitHub URL) or straight from the original public source.

## Copies kept in this folder

| File | Used by | Origin (as credited on the lesson page) | Notes |
|---|---|---|---|
| `AmesHousing.csv` | Ames Housing project | De Cock (2011), *Ames, Iowa: Alternative to the Boston Housing Data*, Journal of Statistics Education 19(3) | Published by the author for teaching use |
| `Crop_recommendation.csv` | Crop project | Kaggle "Crop Recommendation Dataset" | Licence: see the original Kaggle page |
| `Crystal_structure.csv` | Perovskite project | Public ABO3 perovskite distortion table | Cited on the lesson page |
| `Kern_County_bond_dataset.csv` | Municipal bond project | California Debt and Investment Advisory Commission (CDIAC) public issuance records, Kern County | Public agency data |
| `WA_Fn-UseC_-HR-Employee-Attrition.csv` | Flight-risk project | IBM Watson Analytics sample data (fictional employees) | As distributed on Kaggle |
| `WA_Fn-UseC_-Marketing-Customer-Value-Analysis.csv` | Customer-value project | IBM Watson Analytics sample data | As distributed on Kaggle |
| `ab_testing.csv` | A/B testing project | Public landing-page A/B test log (Udacity/Kaggle) | As distributed on Kaggle |
| `click_through_rate.csv` | Click-through project | Kaggle "Ad Click Prediction" advertising data | Licence per the Kaggle page |
| `credit_score_classification.csv` | Credit-score project | Kaggle "Credit Score Classification" | Licence per the Kaggle page |
| `customer_segmentation.csv` | Customer-segmentation project | Kaggle "Credit Card Dataset for Clustering" | Licence per the Kaggle page |
| `train_data_credit_card.csv` | Lead-prediction project | Analytics Vidhya "Credit Card Lead Prediction" practice data (train split) | Unzipped from the original archive |
| `used_car_cardekho.csv` | Used-car project | CarDekho listings (Kaggle "Vehicle dataset from CarDekho") | Licence: see the original Kaggle page |
| `zomato.csv` | Zomato project | Kaggle "Zomato Bangalore Restaurants" | **Slimmed to fit GitHub's file-size limit:** the long free-text `reviews_list` and `menu_item` columns are replaced by a 10-character hash of the original text. Rows, columns, row order and uniqueness are unchanged, and the lesson never reads the text itself |

Please check the licence shown on each original page before reusing a file outside this course.

## Downloaded from the original public source (not copied here)

| Dataset | Source | Why not copied |
|---|---|---|
| Credit-card fraud (`creditcard.csv`, 150 MB) | TensorFlow public mirror of the ULB / Worldline Kaggle dataset | Larger than GitHub's 100 MB limit |
| MovieLens 100K (`u.data`) | https://files.grouplens.org/datasets/movielens/ml-100k.zip | GroupLens does not permit redistribution |
| Pima Indians diabetes | https://raw.githubusercontent.com/jbrownlee/Datasets/master/pima-indians-diabetes.data.csv | Third-party public copy, kept at source |
| Cleveland heart disease | https://archive.ics.uci.edu/ml/machine-learning-databases/heart-disease/processed.cleveland.data | UCI repository |
| Wholesale customers | https://raw.githubusercontent.com/udacity/MLND_CN_P3_Customer_Segments/master/customers.csv | Third-party public copy, kept at source |
| Big Mart sales (`Train.csv`) | https://raw.githubusercontent.com/akki8087/Big-Mart-Sales/master/Train.csv | Third-party public copy, kept at source |
| Insurance claims severity | https://raw.githubusercontent.com/fardil-b/Insurance-Claims-Severity-Prediction/main/dataset.zip | Competition data; kept at source |
| Cafe price optimisation (two files) | https://raw.githubusercontent.com/dasari-mohana-zz/Cafe_Price_Optimization_project/main/ | Third-party public copy, kept at source |
