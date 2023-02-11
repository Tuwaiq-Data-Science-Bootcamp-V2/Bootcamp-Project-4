# Noon Perfume


## Team members

| Team members   | Role |
| ----------- | ----------- |
| Alaa | EDA, Visualization,ML |
| Khalid | Visualization,ML|
| Raghad Alsalamah |Markdown, Visualization,ML |

## Goal:
The aim of this project is to use ML to predict scents of perfumes based on some features. This will help to know the most popular scents of perfume so the sellers can provide these perfume or help producers to produce similar perfume.

## Dataset:
Noon is the lifestyle shopping destination for the region in Saudi Arabia, with the largest online selection of leading brands in categories such as electronics, fashion, health & beauty, fragrances, grocery, baby products, and homeware. Noon is a large online marketplace in the Middle East.
Data was collected from the perfume section for female, male, and unisex departments.This dataset shows the scent notes of perfume in different brands. Since perfume is a product category that has a high profit margin in this region.

The dataset is available through the [kaggle.](https://www.kaggle.com/datasets/monirahabdulaziz/noon-perfume)
## Dataset Description
|  Column  | Description |
| ----------- | ----------- |
| brand| Indicates to the perfume's boutique of each perfume |
| name| Indicates to the name of each perfume |
| old_price|  Indicates to the price of each perfume before sale |
| new_price|  Indicates to the price of each perfume after sale|
| ml| Indicates to the capacity of a perfume bottle |
| concentration| Indicates to the Fragrance concentrations or strengths |
| department|  represent the gender for each perfume, feminine perfume for women, the masculine perfume for men and unisex|
| scents|  Indicates to the represents the general scents for each perfume|
| base_note|  Indicates to the base notes that bring depth and solidity to a perfume.|
| middle_note|  Indicates to the middle note.|
| item_rating | Indicates to item rating. |
| seller | Indicates to seller of perfume. |
| seller_rating | Indicates to seller rating out of 5. |
| num_seller_ratings | Indicates total numbers of buyers. |
| discount% | Indicates to the discount amount percentage. |
| discount_price |  Indicates to the amount of the discount |
| price/ml |  Indicates the price for each capacity |

## Final results of ML models

|  ML model  | Accurecy |
| ----------- | ----------- |
| RandomForestClassifier|0.65  |
| Logistic Regression|0.41  |
| SVC|0.41  |
| KNN|0.38  |
| GaussianNB|0.36  |
| DT|0.61  |

|  ML model  | Mean Error |
| ----------- | ----------- |
| Linear Regression|MAE: 43.38 |
| |MSE: 4147.38 |
| |RMSE: 64.40 |

## The best classification model was the Random Forest with accuracy 65%.
## The best regression model was the Linear with the men errors were:
MAE: 43.38679436056637
MSE: 4147.385233005436
RMSE: 64.40019590812932  .
