# Bootcamp Project 4



## Roles and responsibilities :
| **Role** | **Member(s)** |
| ----------- | ----------- |
| **EDA**  | Hannen and Amjad |
| **Preprocessing**  | Hannen |
| **Visualization**  | Hannen and Amjad |
| **ML**  | Hannen, Amjad and Abdulaziz|
| **Comparison**  | Amjad |
| **Markdown** | Abdulaziz and Amjad |

## Introduction:
This project aims to use machine learning algorithms for prediction purpose. We used classification algorithms to predict the income amount of the loan requester. In addition, we used it to predict loan amounts using regression algorithms.

## Dataset Overview and Source
We choose to work with "2020 Social Loan Data" issued by Saudi Social Development Bank.
The Dataset consist of 15 columns and 13913 rows.
### Coulmns description:														
- 'ID' unique identifiers for each row 
- 'فرع البنك' : Bank branch
- 'نوع التمويل' : Funding type
- 'تصنيف التمويل' : Funding classification
- 'قطاع العميل' : Customer sector
- 'قيمة التمويل' : Loan amount
- 'قيمة القسط' : The value of Installment
- 'تاريخ الصرف' : Exchange date
- 'جنس العميل' : Customer gender
- 'عمرالعميل' : Customer age
- 'الحالة الاجتماعية' : Social status
- 'احتياجات خاصة' : Special need?(yes or no)
- 'عدد افراد الاسرة' : Number of family members
- 'قرض ادخاري' : Savings loan?(yes or no)
- 'قيمة الدخل' : Income value

[DataSource Link](https://od.data.gov.sa/Data/ar/dataset/social-development-bank-loans-for-2020)

## Conclusion 
### Classification to predict 'قيمة الدخل'
| **ML model** | **Accurecy** |
| ----------- | ----------- |
| **Decision Tree**  | 0.51 |
| **Random Forest**  | 0.54 |
### Regression to predict 'قيمة التمويل'
| **ML model** | **R2 score** |
| ----------- | ----------- |
| **Linear regression**  | 0.6 |
| **Logistic regression**  |  -0.004 |
