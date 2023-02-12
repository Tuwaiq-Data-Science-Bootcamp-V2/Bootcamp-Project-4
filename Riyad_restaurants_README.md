
# <img src="Restaurant.jpeg" width="90" height="90"> | Riyadh restaurants Classification
Riyadh is the capital and largest city in Saudi Arabia, and in the past 10 years it had a huge growth in the food sector with such growth a person would have hard time finding a suitable restaurant that suits his needs and it's within the person's budget.

## Team members
| Team members     | Role                                                                      |
| ---------------- | ------------------------------------------------------------------------- |
| Mohammed Alrajeh |         together           |
| Lolo Almuqbil    |           together    |
| Razan alyahya    | together  |

## Dataset Overview
this [dataset](https://www.kaggle.com/datasets/fahd09/riyadh-restaurants-20k) includes informatin about restaurants in Riyadh (scrapped from foursquare.com) such as their categories and the price range of the restaurant. The dataset has 11 columns and 19.4k rows.

## Dataset Description
| Column               | Description                                                                                                                                                              |
| -------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| name                 | The name of the restaurant. Some names are only available in Arabic.                                                                                                                                                        |
| categories             | The list of categories (in English) separated by a comma.                                                                                                                                                           |
| address      | The address according to foursquare. Unfortunately, it is the least useful column in the dataset because lots of resutrants lack a formal address. The future version of this dataset may include an enhanced address format.                                                                                                                                                          |
| lat            |Latitude                                                                                                                           |
| lng                | Longitude                                                                                                                        |
| price            | shows the price category (Cheap, Moderate, Expensive, Very Expensive)                                                                                                                            |
| likes  | The number of likes.                                                                                                                           |
| photos  | The number of photos. Photos themselves are not included.                                                                                                                            |
| tips          | The number of tips in Foursquare (e.g., Don't miss their pasta). Tips themselves are not included.                                                                                                                                                                               |
| rating          | The average rating out of 10.                                                                                                                                                  |
| ratingSignals         | The number of raters.                                                                                                |

## ML models comparison
| Model               | Accuracy                                                                                                                                                              |
| -------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
KNN	|0.717568
Decision Tree	|0.678621
Random Forest|	0.768563

## The reason for choosing the ML Models:
- KNN is a popular machine learning model and simple to learn as we have no prior experience with ML before the bootcamp, and from what we have read it performs well with small datasets.
- Decision trees are excellent tools for helping us to choose between several feature and decisce at the end which price category is the restaurant.
- Random Forest gives us the final predictions are either the majority predictions or the average of all the predictions made by decision trees.
