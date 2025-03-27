# Project Title: Bike Purchase Analysis by Demographic Factors
The objective of this project is to analyse the relationship between bike purchases and demographic factors.
Dataset:
The dataset comprises multiple demographic variables to analyse bike purchase behaviour. The following attributes were included:

- **Income**: The income level of customers.
- **Children**: The number of children the customer has.
- **Education**: The education level of the customer.
- **Occupation**: The occupation of the customer.
- **Home Owner**: Whether the customer owns a home (Yes/No).
- **Cars**: The number of cars the customer owns.
- **Commute Distance**: The distance the customer commutes daily.
- **Region**: The geographical region where the customer resides.
- **Age**: The age of the customer.
- **Age Brackets**: Categorised age ranges for analysis (e.g., Adolescence, Middle Age, Old).
- **Purchased Bike**: Whether the customer purchased a bike (Yes/No).

- Format on Marrital Status, Age, Income, Education and Commute distance were changed.
- Formulas used to edit raw data (Age)
- Age Bracket: =IF(L2>55,"Old",IF(L2>=31,"Middle Age",IF(L2<31,"Adolescence","Invalid")))

### Key Performance Indicators (KPIs):
- In Pivot Table:
- **Average Income by Demographic Factors**: Examining income distribution across different variables such as gender, age, and occupation.
- **Bike Purchase Behaviour by Commute Distance**: Analysing how commute distance impacts bike purchases.
- **Bike Purchases by Age Group**: Understanding bike purchase behaviour based on age brackets.
- In slicer:
- **Impact of Home Ownership on Bike Purchases**: Analysing whether homeownership influences the likelihood of purchasing a bike.
- **Education and Occupation Impact on Purchases**: Investigating whether education or occupation plays a role in bike purchase decisions.

### Insights:
#### Income Analysis:
- Female customers had an average income of $54,331, while male customers had a higher average income of $58,000. The overall average income across all customers is $56,209.

#### Bike Purchase by Commute Distance:
- Customers living within 0-1 miles recorded the highest number of bike purchases (207). In contrast, customers living more than 10 miles away purchased the fewest bikes (33).

#### Bike Purchases by Age Group:
- The **Middle Age** group (30-50 years) had the highest number of bike purchases (739), followed by the **Old** group (50+ years) with 175 purchases. The **Adolescence** group (18-29 years) had the fewest purchases (112).

#### Education & Occupation:
- There was a positive correlation between higher education levels (college degrees or above) and an increased likelihood of purchasing bikes. Occupations such as professionals and managers exhibited a higher tendency to purchase bikes.

### Dashboard and Visualisations:
The project utilises pivot tables and interactive charts to summarise the relationships between income, age, bike purchase status, and other demographic factors. This enables stakeholders to quickly understand trends and make informed decisions.

### Conclusion:
To drive more bike sales, the company should target the **Middle Age** demographic (30-50 years), as they are the biggest purchasers, particularly those with short commutes (0-1 miles). Additionally, marketing efforts should focus on homeowners and individuals with higher educational backgrounds. Tailored campaigns for these segments would likely result in higher conversion rates.

### About:
The project was developed using **Excel**, employing pivot tables and data visualisation techniques to conduct detailed analysis and present the findings in an interactive dashboard format.
