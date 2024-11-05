# Customer-Segmentation-with-Machine-Learning

 This capstone project analyzes 1 million data points in customer analytics to develop strategies that boost retention and satisfaction for ride-hailing companies like Uber and Lyft.



![DALLE2024-11-0514 38 49-Avisuallyappealingimagerepresentingacapstoneprojectoncustomersegmentationinride-sharingshowcasingkeytermslikeMachineLearningUb-ezgif com-webp-to-jpg-converter](https://github.com/user-attachments/assets/b92377ae-c52b-4c58-9670-53d333b28c27)


## Dataset:

**Uber-Lyft Dataset:** [Kaggle - Uber and Lyft Dataset (Boston, MA)](https://www.kaggle.com/datasets/brllrb/uber-and-lyft-dataset-boston-ma)

This dataset captures ride-hailing details across Boston, MA, allowing analysis of customer behavior and segmentation based on ride patterns. Key features include ride details, pricing, and other essential ride-sharing attributes.

Our objective is to determine different segments based on their ride patterns and behaviors and create business strategies to help ride companies with the increase in customers. Our primary goal is to help ride companies with the business logic and marketing strategies to achieve the target.

1. **Targeted Marketing Strategies** – offering personalized promotions to boost customer acquisition.
2. **Service Optimization** – enhancing fleet distribution and availability during high-demand times.
3. **Dynamic Pricing Models** – adjusting prices based on demand patterns to maximize revenue.

---

## Customer Segmentation Strategies

We categorize customers using different segmentation approaches to uncover specific trends, such as:
- **Time of Day**
- **Day of the Week**
- **Common Pick-Up and Drop-Off Locations**
- **Cab Types (Uber, Lyft)**
- **Travel Distances (short, medium, long)**

This segmentation enables businesses to design relevant customer retention programs and improve ride-sharing experiences.

---

### Segmentation Types

1. **Time Segment**
   - Identifies commuters by time of day (e.g., morning, evening).
   - Allows targeting of peak travel hours with special offers.
   
2. **Day Segment**
   - Groups travelers by weekday or weekend, enabling targeted promotions (e.g., weekend discounts).
   
3. **Source Segment**
   - Clusters common pick-up points for shared rides, potentially reducing wait times.
   
4. **Destination Segment**
   - Clusters common drop-off locations, facilitating ride-sharing options for popular destinations.
   
5. **Cab Type Segment**
   - Compares preference for Uber vs. Lyft, aiding competitive pricing and promotions.
   
6. **Distance Segment**
   - Groups riders by trip distance, enabling companies to offer discounts for longer rides or incentivize loyalty for frequent, shorter trips.

---

## Project Workflow

1. **Data Preprocessing**
   - **Drop Unnecessary Columns:** Remove irrelevant data fields.
   - **Handle Missing Values:** Impute or eliminate missing data to ensure data integrity.
   - **Feature Engineering:** Convert data types as needed and engineer new features for improved model accuracy.

2. **Exploratory Data Analysis (EDA)**
   - Analyze customer behaviors and visualize common ride patterns to inform segmentation.
   - Identify critical factors influencing customer preferences.

3. **Machine Learning Models**
   - Models Tested:
     - **Random Forest Regressor**
     - **Linear Regression**
     - **XGBoost**
   - Evaluation Metrics: MAE, MSE, R-squared

   | Model                  | MAE  | MSE   | R-squared |
   |------------------------|------|-------|-----------|
   | Random Forest Regressor | 7.09 | 76.66 | 0.12      |
   | XGBoost                | 7.09 | 76.66 | 0.12      |
   | Linear Regression      | 7.17 | 78.64 | 0.09      |

4. **Model Evaluation and Selection**
   - Both Random Forest and XGBoost yielded strong results, with comparable accuracy.
   - **Random Forest Regressor** was selected as the final model due to its accuracy and stability.

---

## Summary and Key Insights

The analysis of customer behavior across various segments uncovered several actionable insights:
- **Targeted Marketing:** Design campaigns based on segments, such as weekday vs. weekend users, or morning vs. evening commuters.
- **Service Optimization:** Adjust fleet distribution to meet high-demand locations and times.
- **Dynamic Pricing:** Use demand trends to refine pricing strategies, maximizing profit while keeping riders satisfied.
- **Customer Loyalty Programs:** Implement incentive-based programs to retain long-distance and frequent commuters.

---

## Recommendations for Ride-Sharing Companies

1. **Deploy Targeted Marketing Campaigns**: Offer promotions tailored to customer segments (e.g., long-distance riders or weekend travelers).
2. **Optimize Fleet Circulation**: Ensure efficient vehicle availability in high-demand locations during peak hours.
3. **Dynamic Pricing Adjustment**: Leverage demand data to set flexible prices, maintaining competitive rates while maximizing revenue.
4. **Customer Loyalty Programs**: Introduce membership or discount programs for regular and long-distance riders to boost retention and build loyalty.

---


