# Applied Data Portfolio

Welcome to my Applied Data Portfolio. This portfolio features a comprehensive collection of projects and presentations demonstrating my expertise in data engineering, feature engineering, and data science, spanning machine learning, natural language processing (NLP), and reinforcement learning.

Covering multiple domains, each project illustrates my ability to apply cutting-edge techniques and tools to address real-world problems. In instances where data or code is missing, it is typically due to file size constraints or privacy considerations.

Exploring this portfolio will provide insight into the breadth and depth of my advanced data skills. For inquiries or collaboration opportunities, please get in touch with me at kimhyojun@uchicago.edu.

---

## Contents

### Quantitative Finance
- [Action Recommendation System](#action-recommendation-system)

### Reinforcement Learning
- [Electric Vehicle Smart Charge Scheduling](#electric-vehicle-smart-charge-scheduling)

### Natural Language Processing
- [AI's Evolutionary Path: What the Future Holds](#ais-evolutionary-path-what-the-future-holds)
- [Hackathon Project](#hackathon-project)

### Machine Learning
- [eCommerce Customer Segmentation](#ecommerce-customer-segmentation)
- [The Patterns of Paying Debts of Credit Card Clients](#the-patterns-of-paying-debts-of-credit-card-clients)

### Time Series Analysis and Forecasting
- [Predictive Analysis of Bitcoin Returns](#predictive-analysis-of-bitcoin-returns)
- [Unemployment Rate](#unemployment-rate)

### Data Analysis and Visualization
- [Chicago Rideshare Market Analysis](#chicago-rideshare-market-analysis)
- [Statistical Analysis of U.S. Hospital Mortality Rates](#statistical-analysis-of-us-hospital-mortality-rates)

### Software Development
- [The I-Go Application](#the-i-go-application)

---
## Quantitative Finance

### Action Recommendation System
*(Mar. 2024, Time Series/ Natural Language Processing Project)*

- [Presentation (PPT)](https://github.com/mountainmochi/Data_Science_Portfolio/blob/main/Action%20Recommendation%20System%20(ARS)/Action%20Recommendation%20System%20Presentation.pptx)

ARS was designed to simplify trading decisions for retail investors, who typically rely on manual approaches, such as general research or manual market analysis, and gut feel. The goal was to develop a proof-of-concept alert system that provides real-time buy/sell signals for tracked stocks when certain conditions are met. This system integrates methods currently employed by investors and more advanced ML modeling in an automated, real-time system.

The system uses Moving Average Crossover and ARIMA models to generate signals every 60 seconds. It also employs momentum indicators, popular among day trading retail investors, to determine the strength/weakness of a stock's price. Additionally, ARS conducts news sentiment analysis using data from Yahoo and Bing's News Search APIs, processed through a pre-trained FinBERT model. This comprehensive approach aims to make it easier for retail investors to make informed trading decisions.

*Programming Language: Python*

*Libraries: pandas, numpy, matplotlib, scikit-learn, pmdarima, tensorflow, pytorch, nltk, transformers*

---
## Reinforcement Learning

### Electric Vehicle Smart Charge Scheduling
*(Dec. 2023, Reinforcement Learning Project)*

- [Presentation (PPT)](https://github.com/mountainmochi/Data_Science_Portfolio/blob/main/Electric%20Vehicle%20Smart%20Charge%20Scheduling/Final%20Presentation%20.pptx)

This project focused on optimizing electric vehicle (EV) charging systems for the Transportation and Power Systems Division at Argonne National Laboratory (ANL). My team and I enhanced ANL's EV infrastructure by minimizing peak grid demand and maximizing the utilization of cost-effective energy sources via Multi-Objective Linear Programming (MOLP), Epilson-Greedy in Q-Learning (EGQL), and Actor-Critic in Proximal Policy Optimization (ACPPO). 


We achieved a 24.9% reduction in peak power demand with ANL over 42 days, a 70% total charge upon EV arrival, and enhanced EV charging efficiency by 17% via MOLP, EGQL, and ACPPO. The envisioned result was the development of a more resilient, adaptive, and sustainable EV charging ecosystem aligned with the evolving landscape of clean energy and transportation.

*Programming Language: Python*

*Libraries: pandas, numpy, seaborn, matplotlib, pulp, glob, tensorflow, pytorch*

---
## Natural Language Processing

### AI's Evolutionary Path: What the Future Holds
*(Aug. 2023, Natural Language Processing Project)*

- [Presentation (PPT)](https://github.com/mountainmochi/Data_Science_Portfolio/blob/main/AI's%20Evolutionary%20Path%3A%20What%20the%20Future%20Holds/AI's%20Evolutionary%20Path%20-%20What%20the%20Future%20Holds.pptx)

This project employed advanced NLP techniques, including data preprocessing, topic modeling, classification, targeted sentiment analysis, and named entity recognition. These techniques were applied to a comprehensive analysis of 200,000 news articles.

The analysis revealed the profound impact of AI across various professions and industry sectors. By offering actionable insights and recommendations, the project highlighted the transformative potential of AI in diverse fields.

*Programming Language: Python*

*Libraries: pandas, numpy, scikit-learn, matplotlib, seaborn, gensim, spacy, nltk, pyldavis, tensorflow*

### Hackathon Project
*(May 2023, Natural Language Processing Project)*

- [Python](https://github.com/mountainmochi/Data_Science_Portfolio/blob/main/Hackathon%20Project/Hackathon%20Project.py)

In this project, my partner and I developed an NLP model (BERT) to pinpoint patients likely needing surgery using extensive EMR data.

Utilizing feature engineering for analysis, the model achieved a 73% accuracy in predicting patients who needed surgical requirements. Incorporated, it promised improved early interventions and potential cost savings for healthcare providers.

*Programming Language: Python*

*Libraries: pandas, tensorflow, matplotlib*

---

## Machine Learning

### eCommerce Customer Segmentation
*(Dec. 2022, Machine Learning Project)*

- [Presentation (PPT)](https://github.com/mountainmochi/Data_Science_Portfolio/blob/main/eCommerce%20Customer%20Segmentation/Group3_Final_Presentation_inperson.pptx)

The project focused on improving eCommerce book sales by implementing an AI-powered recommendation engine. The primary objective was to target the top 15% of customers and provide them with personalized book recommendations. These tailored book suggestions were derived from analyzing user purchase history and engagement patterns. The project anticipated a significant sales boost of up to 20% within this targeted customer segment. This initiative was strategically framed as an AI-driven eCommerce personalization strategy, emphasizing the role of advanced algorithms in enhancing the customer experience and driving sales.

With unsupervised clustering and machine learning techniques, the results highlighted the importance of strategic algorithmic updates in the eCommerce domain, boosting sales and creating a more engaging and personalized shopping experience for top-tier customers. This initiative provided valuable guidance for future strategies and emphasized the role of AI in driving eCommerce success.

*Programming Language: Python*

*Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn*

### The Patterns of Paying Debts of Credit Card Clients
*(Dec. 2019, Machine Learning Project)*

- [RStudio (HTML)](https://github.com/mountainmochi/Data_Science_Portfolio/blob/main/The%20Patterns%20of%20Paying%20Debts%20of%20Credit%20Card%20Clients/The%20Patterns%20of%20Paying%20Debts%20of%20Credit%20Card%20Clients.pdf)

This project predicted the default behavior of credit card clients by analyzing the relationship between independent and dependent variables. The goal was to enhance predictive accuracy and understand variable impacts on debt repayment behavior. The study thoroughly examined correlations using machine learning methods, including box plots, logistic and probit classifications, ridge, lasso, tree, bagging, random forest, boosting, XG boost, support vector machine, and neural networks.

After evaluating the ML models and their accuracy/error rates, the XG boost model emerged as the most effective choice, achieving the lowest error rate of 0.177. This model revealed significant coefficients and associations related to genders, education levels, age groups, and debt repayment tendencies.

*Programming Language: R*

*Libraries: glm, glmnet, class, tree, randomForest, e1071, tensorflow, keras*

---

## Time Series Analysis and Forecasting

### Predictive Analysis of Bitcoin Returns
*(May 2023, Time Series Project)*

- [Presentation (PDF)](https://github.com/mountainmochi/Data_Science_Portfolio/blob/main/Predictive%20Analysis%20of%20Bitcoin%20Returns/Hyojun_Kim_TS_Final_Project.pdf)

The project analyzed Bitcoin’s historical trade data from January 2012 to March 2021, focusing on minute-to-minute OHLC prices and trade volume. Bitcoin markets were influenced by factors including trade volume and price points; high volume often signaled increased returns, while price fluctuations indicated market volatility.

Models such as ARFIMA, ARIMA, ETS, and SARIMA were employed to achieve accurate forecasting. These models captured market dependencies and integrated past behaviors into predictions, comprehensively understanding Bitcoin market trends.

*Programming Language: R*

*Libraries: dplyr, lubridate, zoo, ggplot2, imputets, forecast, ttr*

### Unemployment Rate
*(Dec. 2020, Time Series Project)*

- [RStudio (HTML)](https://github.com/mountainmochi/Data_Science_Portfolio/blob/main/Unemployment%20Rate/Unemployment-Rate.html)

The project involved a detailed analysis of unemployment rates in the U.S., examining variations across months, states, counties, and years using R. The analysis identified seasonal trends, with higher unemployment rates in winter due to reduced agricultural and construction activities and the lowest rates seen in the fall.

The study also compared unemployment rates among states and counties. Nebraska was found to have the most favorable employment landscape, while Arizona faced challenges due to its heavy reliance on seasonal agriculture and unique federal funding for recognized tribes. At the county level, Steele County in North Dakota and Imperial County in California represented the extremes in employment prospects. The project examined yearly data, indicating sporadic unemployment spikes, especially around 1992 and the early 2010s.

*Programming Language: R*

*Libraries: ggplot2, dplyr*

---

## Data Analysis and Visualization

### Chicago Rideshare Market Analysis
*(Mar. 2023, Data Analysis/Visualization Project)*

- [Presentation (PPT)](https://github.com/mountainmochi/Data_Science_Portfolio/blob/main/Chicago%20Rideshare%20Market%20Analysis/Group%20Project%20-%20Ride%20Share%20Analysis.pptx)

Chicago's rideshare market trends were identified by analyzing an 8-million-record rideshare dataset. There was a clear seasonality influenced by weather and a strong preference for Toyota vehicles in black. Additionally, drivers drove an average ride distance of 4.7 miles.

The emphasis on the importance of regular vehicle inspections underscored the need for safety advocacy. Strategies were formulated to optimize resource allocation and further emphasize safety in the rideshare industry.

*Programming Language: Python*

*Libraries: pandas, numpy, matplotlib*

### Statistical Analysis of U.S. Hospital Mortality Rates
*(Mar. 2023, Data Engineering/ BI Visualization Project)*

- [Presentation (PPT)](https://github.com/mountainmochi/Data_Science_Portfolio/blob/main/Statistical%20Analysis%20of%20U.S.%20Hospital%20Mortality%20Rates/Final%20Project%20Presentation.pptx)

Over 6 months, performance metrics from 4,000 U.S. hospitals were analyzed, focusing on ailments such as heart failure and knee replacements. A BI tool was developed using a 3NF relational database with 11 tables, which was later transformed into a star schema for enhanced BI reporting.

Hospitals can evaluate their performance via KPIs through a Tableau dashboard, comparing themselves against regional or network benchmarks. Preliminary results showed larger hospital networks lagging in some metrics. Challenges included data gaps and a limited study window. Future studies could delve into hospital operations, patient feedback, and Medicare/Medicaid’s influence.

*Programming Language: SQL*

*Tools: Tableau, Excel*

---

## Software Development

### The I-Go Application
*(May 2019, Software Development Project)*

The project involved developing the “I-Go” application using the Google API. The primary objective of this application was to map 28 landmarks across the UIUC campus. This feature provided valuable assistance to visitors as they navigated the campus grounds. The application was developed using Java in Android Studio.

Special attention was given to designing a user-friendly interface that ensured easy navigation and quick access to detailed information about each landmark. Interactive features were implemented to enhance the user experience and improve landmark visualization. These enhancements made the application more engaging and valuable for its users.

*Programming Language: Java*

*Tools: Android Studio, Google API*

---

## Review

This portfolio showcases my ability to address real-world problems by designing and delivering scalable data pipelines and deploying advanced models across practical domains. Each project reflects my technical expertise and capacity to tackle complex, high-impact challenges. If you have any inquiries or potential collaborations, please contact me at kimhyojun@uchicago.edu.
