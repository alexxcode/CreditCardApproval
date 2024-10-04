
# Credit Card Approval

**Understanding the Factors Influencing Credit Card Approvals**

In today's financial landscape, credit card approval decisions play a pivotal role in shaping individuals' access to credit and financial opportunities. To optimize these decisions, it is essential to analyze the factors that influence credit card approval rates. By understanding these factors, financial institutions can develop more accurate and equitable credit scoring models.

This analysis aims to explore the relationship between various demographic, financial, and socioeconomic variables and credit card approval outcomes. Through a comprehensive examination of a credit card dataset, we will seek to identify key predictors of creditworthiness and understand how these factors interact to influence the likelihood of approval.

> [!NOTE]
>  It is important to clarify that the results and conclusions presented here should be used solely for academic or research purposes.


# Data Visualization 

## Distribution of Credit Card Approval by gender

![Distribution of Credit Card Approval by gender](https://github.com/alexxcode/CreditCardApproval/blob/main/images/gender.png)

**Key observations:**

- Female Dominance: There are significantly more females than males in the dataset. The bar corresponding to "F" is much taller than the bar corresponding to "M."

Exact Counts:
- The count of males is approximately 150,000.
- The count of females is approximately 300,000.
This chart suggests that the dataset is heavily skewed towards females, with roughly twice as many females as males represented.

## Distribution of Credit Card Approval by car ownership

![Distribution of Credit Card Approval by car ownership](https://github.com/alexxcode/CreditCardApproval/blob/main/images/car.png)

**Key observations:**

- Higher Percentage of Non-Car Owners: A larger number of individuals in the dataset do not own a car. The bar corresponding to "NO" is taller than the bar corresponding to "YES."

Exact Counts:
- The count of non-car owners is approximately 280,000.
- The count of car owners is approximately 170,000.
This chart suggests that around 60% of individuals in the dataset do not own a car, while 40% do.


## Distribution of Credit Card Approval by home ownership

![Distribution of Credit Card Approval by home ownership](https://github.com/alexxcode/CreditCardApproval/blob/main/images/house.png)

**Key observations:**

- Higher Percentage of Homeowners: A larger number of individuals in the dataset own a house. The bar corresponding to "YES" is taller than the bar corresponding to "NO."

Exact Counts:
- The count of non-homeowners is approximately 150,000.
- The count of homeowners is approximately 300,000.
This chart suggests that around 67% of individuals in the dataset own a house, while 33% do not.


## Relationship between the number of children and total income
![Relationship between the number of children and total income](https://github.com/alexxcode/CreditCardApproval/blob/main/images/relationship.png)

**Key observations:**

General Trend: There appears to be a general trend where total income decreases as the number of children increases. This suggests that having more children may be associated with lower income levels.

Specific Observations:
- The highest average income is seen for individuals with 0 children.
- Income generally decreases as the number of children increases up to around 5 children.
- Beyond 5 children, the income levels start to fluctuate and become more scattered.
- There are some individual variations within each category of the number of children, as indicated by the error bars.


## Distribution of Credit Card Approvals by Number of Children
![Distribution of Credit Card Approvals by Number of Children](https://github.com/alexxcode/CreditCardApproval/blob/main/images/children.png)

**Key observations:**

- Most Approvals for Individuals with No Children: The tallest bar corresponds to individuals with 0 children, suggesting that they have the highest number of credit card approvals.

- Decreasing Approvals with More Children: As the number of children increases, the count of credit card approvals generally decreases. This indicates that individuals with more children are less likely to be approved for credit cards.

- Rapid Decline: The decline in approvals is particularly steep between 0 and 2 children, suggesting a significant drop in approval rates with the addition of even one child.

- Long Tail: The distribution has a long tail, meaning that there are a small number of individuals with a higher number of children who still receive credit card approvals.



## Distribution of Credit Card Approvals by Income Category
![Distribution of Credit Card Approvals by Income Category](https://github.com/alexxcode/CreditCardApproval/blob/main/images/income.png)

**Key observations:**

- Most Approvals for "Working" Individuals: The tallest bar corresponds to the "Working" category, suggesting that individuals with a current job have the highest number of credit card approvals.

- Decreasing Approvals with Lower Income Categories: As we move from "Working" to "Commercial associate," "Pensioner," "State servant," and finally "Student," the count of credit card approvals steadily decreases. This indicates that individuals in lower-income categories are less likely to be approved for credit cards.

- Significant Difference Between "Working" and Others: The difference between the "Working" category and the others is quite substantial, suggesting a strong association between employment status and credit card approval.


## Distribution of Credit Card Approvals by Education Level
![Distribution of Credit Card Approvals by Education Level](https://github.com/alexxcode/CreditCardApproval/blob/main/images/education.png)

**Key observations:**

- Most Approvals for "Secondary / secondary special" Education: The tallest bar corresponds to the "Secondary / secondary special" category, suggesting that individuals with this level of education have the highest number of credit card approvals.

- Decreasing Approvals with Lower Education Levels: As we move from "Secondary / secondary special" to "Higher education," "Incomplete higher," "Lower secondary," and finally "Academic degree," the count of credit card approvals steadily decreases. This indicates that individuals with lower education levels are less likely to be approved for credit cards.

- Significant Difference Between "Secondary / secondary special" and Others: The difference between the "Secondary / secondary special" category and the others is quite substantial, suggesting a strong association between education level and credit card approval.


## Distribution of Credit Card Approvals by Marital Status
![Distribution of Credit Card Approvals by Marital Status](https://github.com/alexxcode/CreditCardApproval/blob/main/images/marital.png)

**Key observations:**

- Most Approvals for "Married" Individuals: The tallest bar corresponds to the "Married" category, suggesting that married individuals have the highest number of credit card approvals.

- Decreasing Approvals for Other Categories: As we move from "Married" to "Single / not married," "Civil marriage," "Separated," and finally "Widow," the count of credit card approvals steadily decreases. This indicates that individuals in these other categories are less likely to be approved for credit cards.

- Significant Difference Between "Married" and Others: The difference between the "Married" category and the others is quite substantial, suggesting a strong association between marital status and credit card approval.


## Distribution of Credit Card Approvals by House Type
![Distribution of Credit Card Approvals by House Type](https://github.com/alexxcode/CreditCardApproval/blob/main/images/HouseType.png)

**Key observations:**

- Most Approvals for "House / apartment" Residents: The tallest bar corresponds to the "House / apartment" category, suggesting that individuals living in houses or apartments have the highest number of credit card approvals.

- Decreasing Approvals for Other House Types: As we move from "House / apartment" to "Rented apartment," "Municipal apartment," "With parents," "Co-op apartment," and finally "Office apartment," the count of credit card approvals steadily decreases. This indicates that individuals living in these other types of housing are less likely to be approved for credit cards.

- Significant Difference Between "House / apartment" and Others: The difference between the "House / apartment" category and the others is quite substantial, suggesting a strong association between house type and credit card approval.


## Distribution of Credit Card Approvals by Work Phone Possession
![Distribution of Credit Card Approvals by Work Phone Possession](https://github.com/alexxcode/CreditCardApproval/blob/main/images/workphone.png)

**Key observations:**

- Most Approvals for Individuals Without Work Phones: The taller bar corresponds to the "NO" category, suggesting that individuals who do not have a work phone have a higher number of credit card approvals.

- Fewer Approvals for Individuals with Work Phones: The bar corresponding to the "YES" category is significantly shorter, indicating that individuals who do have a work phone are less likely to be approved for credit cards.                      


## Distribution of Credit Card Approvals by Phone Possession
![Distribution of Credit Card Approvals by Phone Possession](https://github.com/alexxcode/CreditCardApproval/blob/main/images/phone.png)

**Key observations:**

- Most Approvals for Individuals Without Phones: The taller bar corresponds to the "NO" category, suggesting that individuals who do not have a phone have a higher number of credit card approvals.

- Fewer Approvals for Individuals with Phones: The bar corresponding to the "YES" category is significantly shorter, indicating that individuals who do have a phone are less likely to be approved for credit cards.


## Distribution of Credit Card Approvals based on whether applicants have an email address 
![Distribution of Credit Card Approvals by Email](https://github.com/alexxcode/CreditCardApproval/blob/main/images/email.png)

**Key observations:**

- Most Approvals for Individuals Without Emails: The taller bar corresponds to the "NO" category, suggesting that individuals who do not have an email address have a higher number of credit card approvals.

- Fewer Approvals for Individuals with Emails: The bar corresponding to the "YES" category is significantly shorter, indicating that individuals who do have an email address are less likely to be approved for credit cards.


## Distribution of Credit Card Approvals by Family Members
![Distribution of Credit Card Approvals by Family Members](https://github.com/alexxcode/CreditCardApproval/blob/main/images/fammembers.png)

**Key observations:**

- Most Approvals for Individuals with Fewer Family Members: The tallest bars correspond to the categories with lower numbers of family members (1, 2, and 3). This suggests that individuals with fewer family members are more likely to be approved for credit cards.

- Decreasing Approvals with More Family Members: As the number of family members increases, the count of credit card approvals generally decreases. This indicates that individuals with larger families are less likely to be approved for credit cards.

- Rapid Decline: The decline in approvals is particularly steep between 0 and 2 family members, suggesting a significant drop in approval rates with the addition of even one family member.

- Long Tail: The distribution has a long tail, meaning that there are a small number of individuals with a higher number of family members who still receive credit card approvals.



**Through a comprehensive analysis of the credit card dataset, we have gained valuable insights into the factors that influence credit card approval rates. Our analysis revealed significant relationships between various demographic, financial, and socioeconomic variables and the likelihood of approval.**


## Next Steps: Building a Predictive Model

**Model Selection and Development**

Based on the insights gained from the data analysis, we will now proceed to develop a machine learning model capable of accurately predicting credit card approvals. A variety of algorithms, including logistic regression, decision trees, random forests, and gradient boosting machines, will be considered.


**Machine Learning Model Development** 

Building upon these insights, we will now proceed to develop machine learning models to predict credit card approvals. By leveraging the curated dataset and applying appropriate algorithms, we aim to create a predictive model that can accurately assess the creditworthiness of applicants.

**Model Selection and Evaluation**

We will carefully select and evaluate different machine learning algorithms, considering factors such as accuracy, precision, recall, F1-score, and interpretability. The goal is to identify a model that provides the best performance while maintaining transparency and explainability.

**Model Deployment and Impact**

Once a satisfactory model is developed, it can be deployed into a production environment to assist in credit card approval decisions. The implementation of such a model can lead to more efficient and accurate credit risk assessments, reducing the likelihood of approving high-risk applicants and improving overall financial stability.