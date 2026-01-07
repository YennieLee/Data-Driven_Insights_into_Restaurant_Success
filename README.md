# Data-Driven_Insights_into_Restaurant_Success 🍽️

## 🔍 Overview
This project aims to identify **what drives success in the restaurant industry** in the United States. Running a restaurant is challenging — around 30% of restaurants in the U.S. close within their first three years.

To uncover key strategies for success, I analyzed restaurant review data containing more than **2.7 million reviews** across the U.S.

The findings are designed to support **restaurant owners and operators** in making data-driven decisions to improve long-term performance.

The analysis was conducted in four main steps:

1. **Defined three custom performance metrics** for restaurants — *stability score*, *loyalty score*, and *reliability score*.
2. **Validated custom metrics** using statistical testing
3. **Identified key features** that positively or negatively impact each metric.
4. **Translated analytical insights into actionable recommendations** for restaurant operators.

Detailed information, such as statistical testing and machine learning performance, is included in the presentation materials.
<br><br><br>

---
<br>

## 🗂 About the Dataset
<img width="2025" height="1135" alt="image" src="https://github.com/user-attachments/assets/7b183530-e8a1-4443-8da6-9d60f1d8022d" />

- **Source**: Yelp Open Dataset
- **Raw data**
    - ~150K business records
    - ~6.9M review records (2005–2022)
- **Filtering criteria**
    - Restaurant businesses only
    - Minimum of 25 reviews per restaurant
- **Final dataset**
    - ~20K restaurants
    - ~2.7M reviews
<br><br><br>

---
<br>

## 🎯 Restaurant Performance Metrics
### 1. Stability Score
- The stability score measures a restaurant’s operational resilience — its ability to withstand and recover from negative events such as rating drops or critical reviews.
- Higher stability scores are associated with lower closure probabilities.
  <img width="567" height="453" alt="image" src="https://github.com/user-attachments/assets/216346eb-bd08-4e44-b295-22047b7158c7" />
<br>

### 2. Loyalty Score
- The loyalty score reflects how beloved a restaurant is — how many regular customers it has and how often they visit.
- Restaurants with higher loyalty scores tend to maintain higher average ratings.
  <img width="630" height="470" alt="image" src="https://github.com/user-attachments/assets/44abc19f-9bc1-40aa-8075-6bdb1cd1a7d2" />
<br>

### 3. Reliability Score
- The **Reliability Score** captures how credible a restaurant appears to potential customers by measuring the share of reviews written by influential reviewers.
- Restaurants with higher reliability scores attract more first-time visitors and accumulate more reviews.
  <img width="571" height="453" alt="image" src="https://github.com/user-attachments/assets/ef13fe54-083e-4651-adbd-0cae6462c666" />
<br><br><br>

---
<br>

## 💡 Insights Deep Dive
### 1. Stability Score
| Insight 1️⃣                                     | Insight 2️⃣                                    |
| ---------------------------------------------- | ---------------------------------------------- |
|• Sentiment of reviews has the strongest impact |• Moderate category variety improves stability |
|<img width="589" height="490" alt="image" src="https://github.com/user-attachments/assets/39075492-affe-4405-8afe-67fdc72252c2" />|<img width="589" height="490" alt="image" src="https://github.com/user-attachments/assets/c6c267ba-b3c9-45ab-bbc6-745657b3c7fd" />|

| Insight 3️⃣                                     | Insight 4️⃣                                    |
| ---------------------------------------------- | ---------------------------------------------- |
|• Restaurants without alcohol service tend to be more stable |• Excessively long operating hours negatively affect stability |
|<img width="589" height="490" alt="image" src="https://github.com/user-attachments/assets/21de05b2-ebf3-46bb-a0b9-a87633a3c469" />|<img width="589" height="490" alt="image" src="https://github.com/user-attachments/assets/553b9117-9fc1-4c46-b455-a3886d469375" />|

<br>

### 2. Loyalty Score
| Insight 1️⃣                                     | Insight 2️⃣                                    |
| ---------------------------------------------- | ---------------------------------------------- |
|• Review volume is the strongest predictor of loyalty |• Outdoor seating and group-friendly environments increase repeat visits |
|<img width="589" height="490" alt="image" src="https://github.com/user-attachments/assets/bbebff35-c3a2-4f60-a85e-24c9236b7dbe" />|<img width="589" height="490" alt="image" src="https://github.com/user-attachments/assets/639be556-a74a-47e3-8646-ea1c19eb0a5c" />|

| Insight 3️⃣                                     | Insight 4️⃣                                    |
| ---------------------------------------------- | ---------------------------------------------- |
|• Alcohol service increases loyalty, despite reducing stability |• Unclear ambience correlates with lower loyalty |
|<img width="589" height="490" alt="image" src="https://github.com/user-attachments/assets/c95e237d-738e-4fdc-84b2-341e8fb3c7f5" />|<img width="589" height="490" alt="image" src="https://github.com/user-attachments/assets/a243aa17-60b2-4798-a0b8-f9b1d6a1a17d" />|

<br>

### 3. Reliability Score
| Insight 1️⃣                                     | Insight 2️⃣                                    |
| ---------------------------------------------- | ---------------------------------------------- |
|• Breadth of food categories is the most influential factor |• Restaurants serving familiar, mainstream cuisines achieve higher reliability |
|<img width="589" height="490" alt="image" src="https://github.com/user-attachments/assets/1da3bef4-91ea-40e2-bf55-bf16108e1909" />|<img width="589" height="490" alt="image" src="https://github.com/user-attachments/assets/465c6ad0-81a4-4f30-bb7a-413351b93d13" />|

| Insight 3️⃣                                     | Insight 4️⃣                                    |
| ---------------------------------------------- | ---------------------------------------------- |
|• Quality of reviews matters more than sheer quantity |• A high number of low-quality reviews negatively affects the reliability score |
|<img width="589" height="490" alt="image" src="https://github.com/user-attachments/assets/0b632dee-7c5c-422e-adf1-ad8c50106cb2" />|<img width="589" height="490" alt="image" src="https://github.com/user-attachments/assets/f593d91e-d116-486a-9780-fc9b28127d51" />|

<br><br><br>

---
<br>

## 🪄 Recommendations
### 1. Improving Stability 📈
- Focus on core menu offerings rather than excessive variety.
- Monitor customer feedback closely and address recurring complaints.
- Consider regular off-days for more stable operations
- Be cautious with alcohol service depending on target customer base
<br>

### 2. Building Loyalty 💖
- Invest in outdoor seating and group-friendly layouts
- Develop a clear and consistent brand atmosphere or concept.
- Offer alcohol where it aligns with the restaurant’s concept and audience.
<br>

### 3. Enhancing Reliability 🛡️
- Encourage high-quality, thoughtful customer reviews.
- Balance uniqueness with familiarity in menu design.
- Prioritize accessible cuisine before expanding into niche categories (e.g., fusion concepts).
