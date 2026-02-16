# 📊 JobAaj Data Analytics Projects Portfolio

Welcome to my Data Analytics project repository.  
This repository contains multiple end-to-end analytics projects covering EDA, visualization, dashboarding, and business insights using Python, SQL, Excel, and Power BI.

---

## 🚀 Projects Included

### 1️⃣ Adecco HR Analytics
Problem Statement:
Analyze employee attrition and job satisfaction data to identify key factors driving turnover among junior-level employees and provide actionable recommendations to improve retention at Adecco India.


Steps taken:
- Analyzed HR dataset to understand employee attrition patterns.
- Identified key drivers affecting employee turnover.
- Tools Used: Excel


Key Insights & Conclusion:
-There is Overall 16% of attrition rate in the company
-Sales dept has the highest attrition rate.
-Male has slightly more attrition rate than female, whereas singles are attriting more than married and divorcees.
-Younger employees are more likely to leave, as age of employees increases, attrition decreases, old people are less likely to leave and stay for stabilty.
-As monthly income increases, attrition decreases as there is weak negative relationship.
-As no. of years increases, attrition decreases as there is weak negative relationship.
-Both young and older employees can be dissatisfied or satisfied, There is no strong age pattern.

Detailed analysis in the code attached in folder



-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------

### 2️⃣ Sales data analysis--Final Exam Project
Problem Statement:
The e-commerce company is facing multiple operational challenges that hinder growth and customer satisfaction & to address these issues, the company is leveraging data-driven insights to optimize operations.
.
Steps:

- Complete data analysis workflow from data cleaning to insights.
- Business-driven insights and recommendations.
- Tools Used: Python, Jupyter Notebook
-for better analysis I summarized data into 3 categories-Is cancelled-"Cancelled", "Shipped - Returned to Seller",
                                        "Shipped - Rejected by Buyer","Shipped - Returning to Seller.
order successful - "Shipped - Delivered to Buyer", "Shipped"
In process - "Shipped - Lost in Transit", "Shipped - Out for Delivery",
     "Shipped - Picked Up","Pending","Pending - Waiting for Pick Up","Shipped - Damaged","Shipping"

Key Insights & Conclusion:

- As per the histogram, we can see 250-1000 is the range which most of the people Ordering, Also as per the box plot there are also outliers where people have Ordered worth more than 3k.
- Most of the people have accepted the delivery than cancelling it.
Majorly fullfilled by amazon, followed by expedited facilty.Set & kurta seems to be the most ordered items.
Size M is the most ordered size indicating there are more of M size people.Highest no. of orders coming from maharashtra, karnataka, tamil nadu.
- As per the status, nearly 70 million worth amount is shipped or accepted by customers generating the revenue for the company, whereas more than 10million 
worth is either cancelled, returned or in process.
- weekdays has more no. of orders having generating higher revenue as compared to weekends , whereas average order value is more for weekends.
- AN201,AN202, AN203, AN204, AN205 are top 5 category which are slow movers.
- Amazon has completed more fulfilments than merchants.

Detailed analysis in the code attached and power point in folder

--------------------------------------------------------------------------------------------Module solutions---------------------------------------------------------------------------------

### 3️⃣ Google Play Store App Analysis

Problem Statement:
Analyze Google Play Store app data to uncover trends in ratings, reviews, and features that can guide app development strategy, improve user experience, and increase downloads and revenue.


Steps:
- Analyzed app ratings, installs, reviews, and categories.
- Handled missing values and performed category-level analysis, changed datatypes to their proper format while extracting info like year & month, then cleaned size & install column to pull size and no. of installs to perform analysis.
- Built visualizations to detect trends and outliers.
- Tools Used: Pandas, NumPy, Matplotlib, Seaborn

Key Insights & conclusion:

-Mostly 0-20mb size apps are downloaded.
- 92% of apps are free.
- Facebook,skype,google drive, google news, youtube are most installed apps.
- Free apps has 3 times more reviews than paid ones.
- categories like game, family, travel & local, sports, entertainment having the largest file size.
- With increase in ratings , no. of installs also increases majorly between 4.0 to 4.5.
- Some small apps are among the most downloaded apps in the store. Large size does not prevent high installs, but fewer apps achieve it.

Detailed analysis in the code attached in folder.

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

### 4️⃣ Heart Health Analysis

Problem Statement:
Elite Hotels International, a prominent player in the hospitality industry, has been facing challenges in managing its booking patterns and customer satisfaction. With hotels spread across various locations, understanding booking trends and guest behavior is crucial for optimizing operations and enhancing guest experience. The management has decided to conduct a comprehensive data analysis of their booking data to uncover insights that can drive strategic decisions.

Steps:
- Explored relationship between medical features and heart disease target.
- Correlation analysis and predictive insights.
- Tools Used: Python, EDA, Statistical Analysis

Key Insights & conclusion:
- Female have higher resting blood pressure.
- There is weak positive relationship between age and cholesterol.
- Late 50's patients showing all kinds of chest pain variants.
- Heart disease cases are more concentrated in middle-aged individuals (50–60), suggesting risk rises significantly after 45. Cholesterol alone does not clearly separate heart disease vs non-disease groups — indicating weak standalone predictive power.

Detailed analysis in the code attached in folder.

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

### 5️⃣ Hospital Admission Analysis

Problem Statement:
Analyze hospital admission data at Novartis to identify factors driving high patient readmission rates and provide insights to improve care quality while reducing unnecessary healthcare costs.

Steps:
- Investigated re-admission patterns and operational metrics.
- Identified trends for better hospital resource planning.
- Tools Used: Python, Data Visualization

Key Insights & Conclusion:
- Readmission rate is high for 70-80 yrs old.
- Pediatrics-Pulmonology,PhysicalMedicineandRehabilitation,OutreachServices,Pathology,Psychiatry-Addictive has longest avg days Pediatrics-EmergencyMedicine, Anesthesiology-Pediatric,
  Anesthesiology, Speech, DCPTEAM has shortest avg days.
- 40% of patients re admitted in 30 days.
- patients having changed their diabetic medication are more prone to re admission.
- Cacausian & AfricanAmerican showing higher admission rate both for male & female indicating poor healthcare facilities or poor health in general due to which either they are not able to    recover or fall sick frequently.
- Patients weighing between 75-100 kg are getting readmitted is more than any other category.
- Encounters involving higher medication counts tend to have longer stays. Additionally, readmitted patients consistently exhibit longer lengths of stay for comparable medication levels, indicating greater clinical complexity. This suggests that medication volume can serve as an important predictor of both prolonged hospitalization and readmission risk.

Detailed analysis in the code attached in folder.

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

### 6️⃣ Problem Statement:
Analyze Porter Delivery operational data to identify root causes of declining delivery-time satisfaction and provide data-driven recommendations to improve customer experience and protect market share.

Steps:
- Delivery performance and operational analytics.
- Explored market-level patterns and performance indicators.
- Tools Used: Python, Data Cleaning & EDA

Key insights & conclusion:

- Italian, Spanish, Caribbean, brazilian, belgian are top 5 category taking more than 50 mins to deliver which shows either operational challenges for these stores of these categories like too many orders, partners not available to deliver,could be far away from the location of orders.
-- Saturday & sunday sees the most orders count.
-On an avg nearly 42-50 mins on an avg is taken to deliver.
- Hourly order volume has a 0.95 correlation with busy partners, indicating highly responsive capacity scaling.
- This analysis shows that with increase in the volume , no. of onshift partners also increases or remains more. Hour-wise demand and partner utilization show a ~0.90 correlation, indicating strong operational alignment between order inflow and rider availability, though some variance remains during peak periods.
- Moroccan, cheese, Burmese, irish, Italian are top categoring where more than 60% orders are above avg no. of orders.
- Onshift vs Busy: 0.998-Markets with more onshift partners also have more busy partners. Onshift vs Delivery Time: –0.43 ,More onshift partners → faster deliveries. Busy vs Delivery Time: –0.38 ,More busy partners → slightly faster delivery. Onshift and busy partners are almost perfectly correlated, indicating redundancy. Both show moderate negative correlation (~–0.4) with delivery time, suggesting partner availability helps but is not the primary driver.

Detailed analysis in the code attached in folder.

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

### 7️⃣ Telecommunication Churn Analysis

Problem statement:
Analyze Airtel customer data to identify key drivers of churn and provide actionable insights to improve customer retention and protect revenue.

Steps:
- Analyzed churn behavior using customer service calls, plan types, and usage metrics.
- Segmented customers to understand churn drivers.
- Business recommendations to reduce churn.
- Tools Used: Python, Pandas, Feature Engineering

Key insights & conclusion:
- Those who have not taken the international plans , are retaining more as compared to those who have taken the international plain and churning more.
- Significant difference in average customer service calls for both the groups(churned & non-churned).
- Day charges are more as compared to evening & night charges.
- difference in total day minutes between churned and non-churned customers is EXTREMELY statistically significant.
- Customers making more than three calls exhibit churn rates above 50%, compared to only 11% for low-contact customers. This suggests that repeated service issues are a major churn driver, and early intervention after the third call could significantly reduce customer attrition.
- International calls have almost no effect here.

* Low international callers churn MORE than high callers.
* International calls affect churn differently by plan
* Biggest churn comes from unused international plans

Detailed analysis in the code attached in folder

### 7️⃣ Google App dashboard creation using power bi

Analyze Google Play Store app data to uncover trends in ratings, reviews, and features that can guide app development strategy, improve user experience, and increase downloads and revenue.

Steps:
After analysing & cleaning the data as discussed earlier, I pushed the final features to sql and then connected to power bi to build dashboard.
 -  

---

## 🛠️ Skills Demonstrated

- Data Cleaning & Preprocessing
- Exploratory Data Analysis (EDA)
- Statistical Analysis
- Data Visualization
- Business Insight Generation
- power bi Dashboard Development
- Problem Solving

---

## 📌 Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- Power BI
- Excel
- SQL

---

## 👩‍💻 About Me

I am a Data Analyst with experience in data analytics with 8 years of experience in banking(Cards & Payments):

Technical skills
- SQL
- Python
- Power BI
- Excel
- AWS Cloud Basics
- Marketing & Banking Data Analytics

I focus on transforming raw data into actionable business insights.

---

## 📬 Contact

📧 mousumidash.2010@gmail.com  +91-8926149994

---

⭐ If you found this repository helpful, feel free to star it!
