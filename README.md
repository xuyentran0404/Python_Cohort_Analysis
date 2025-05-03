# Python_Cohort_Analysis
## I. Introduction
Using Python to analyze transaction data to evaluate user engagement from customer's first transaction
### 1. Dataset
Dataset includes 5 different related tables, including: campaign, customer, device_detail, status_detail, ticket_history
- Ticket History information dataframe
![image](https://github.com/user-attachments/assets/eeeb288f-6714-4da2-96a5-973d1cacaec3)
- Customer information dataframe
![image](https://github.com/user-attachments/assets/1ca8f96b-9955-4f19-ac1b-f26110eee83d)
- Device information dataframe
![image](https://github.com/user-attachments/assets/70166a48-1ad3-45bc-91e7-bb96ceb36756)
- Campaign information dataframe
![image](https://github.com/user-attachments/assets/3947ac0f-f3c1-4909-a148-183cb304cf7e)
- Status information dataframe
![image](https://github.com/user-attachments/assets/a80e91da-f1e9-4129-bffe-69a5ef327092)
### 2. Method: Cohort Analysis  
**Cohort analysis definition**  
- Cohort analysis is a type of behavioral analytics in which you take a group of users and analyze their usage patterns based on their shared traits to better track and understand their actions.
- A cohort is simply a group of people with shared characteristics.  
**Three major types of Cohort**
- Time cohorts: customers who signed up for a product or service during a particular time frame.
- Behavior cohorts: customers who purchased a product or subscribed to a service in the past.
- Size cohorts: refer to the various sizes of customers who purchase the company’s products or services.  
**Cohort type of this project**  
- This project focuses on performing a Cohort Analysis based on Time
- Customers will be divided into acquisition cohorts depending on the month of their first purchase (cohort month)
- The cohort index would then be assigned to each of the customer’s purchases, which will represent the number of months since the first transaction
---
## II. Data Visualization with Python  
Because of the lack of data in 2020 and 2020 (due to the COVID pandemic), I analyzed data from 2019 and 2022  

![image](https://github.com/user-attachments/assets/248f7253-7279-4d6b-9098-14310015717a)
![image](https://github.com/user-attachments/assets/4f0faf00-fe4f-4541-98ac-bd9cfe6a3194)
---
## III. Insights
### 1. Retention Trends in 2019
- **Sharp Decline in Early Months:** After the first month (100%), retention rates fall drastically, typically dropping below 5% by Month 2 and continuing to decrease steadily.
- **Low Long-term Retention:** Most cohorts fall below 3% retention by Month 5 or 6, indicating limited customer stickiness.
- **No Strong Cohorts:** None of the monthly cohorts show consistent or improving retention trends. Even large acquisition months like May and April (3226 and 2922 users) don’t retain well.
- **Volatile Retention:** The rate fluctuates (e.g., Jan’s Month 6 jumps to 3% then down again), suggesting inconsistency in user experience or product engagement.
### 2. Retention Trends in 2022
- **Improved Short-Term Retention:** Many cohorts in 2022, especially Jan, Mar, and Apr, show stronger early-month retention (e.g., 7%, 5%, 5% in Month 1).
- **Slightly Better Long-Term Retention:** Some cohorts maintain 3–5% retention up to Month 6–8, an improvement over 2019.
- **More Stable Behavior:** Retention values don’t fluctuate as wildly, indicating a more consistent customer experience.
- **High Acquisition, Mixed Retention:** Despite a surge in new users in mid-2022 (e.g., July: 13,630), retention remains low (~2–3%), revealing a potential gap between marketing and product delivery.
---
## IV. Recommendations
### 1. Onboarding Experience Optimization
- Users drop off sharply after the first interaction. Improve onboarding journeys, with clear value propositions and smoother first-time experiences.
- Use interactive guides, in-app tutorials, and early incentives to help users understand how to derive value quickly.
### 2. User Segmentation & Targeted Engagement
- Segment customers by behavior (e.g., active vs. churn-risk users) and run personalized email/SMS/web campaigns.
- Use RFM or cohort-based behavior triggers to re-engage customers within the first 2–3 months of drop-off.
### 3. Improve Product Stickiness
- Add habit-forming features: notifications, progress tracking, and gamification.
- Identify and amplify “aha moments”—core value interactions that lead to retention—and ensure users hit them early.
### 4. Leverage Feedback Loops
- Run surveys or usability tests for cohorts with low Month 2–3 retention to identify pain points.
- Deploy exit-intent surveys or follow-up feedback for churned users.
### 5. Lifecycle Marketing Automation
- Implement automated retention flows (email, in-app nudges) for users at risk of churn.
- Re-engage dormant users with value-based messages or exclusive offers.
### 6. Continuous Monitoring & Testing
- A/B test onboarding flows, feature releases, and content delivery methods to identify what improves retention.
- Visualize monthly cohort KPIs over time to track the impact of initiatives.
---
