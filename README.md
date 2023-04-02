# Data Analyst Portfolio
Welcome to my portfolio of data analysis projects! 

This portfolio showcases my skills as a data analyst and provides examples of how I have applied these skills to real-world problems. Each project included in this portfolio demonstrates my ability to manipulate, clean, analyze, and visualize data in order to extract insights and make data-driven decisions.


## Table of Contents

- [Project 1: Interactive Dashboard for Bank Customer Segmentation (RU, ENG)](#project-1)
- [Project 2: A/B Test Evaluation for Recommender System (RU, ENG)](#project-2)
- [ExtraProjects in Russian: Various projects (RU)](#project-extra)

## Projects

### Project 1: Interactive Dashboard for Bank Customer Segmentation<a name="project-1"></a>
This project is graduation project for the Data Analysis Professional Training Course at Practicum INO CPE “Yandex EdTech“ which covered a variety of topics including Python, SQL, Tableau, and business data analytics, totalling 350 hours of instruction.
#### Project Description
Project focuses on analyzing 10,000 bank customers, creating customer segments, statistical analysis and new product recommendations. 
Project involves building an interactive dashboard for analyzing customer segments for Bank Metanprom and creating a presentation. 
The dashboard provides insights on customer behavior and recommends specific products that might be of interest to different customer segments.

#### Project Language
English, Russian

#### Project files
01. [Analysis (Jupyter Notebook in English)](https://github.com/Zliubov/data_analyst_projects/blob/2fa2f8fc8d844f86e08d7b8927fb33f3707b5d34/Project%201:%20Interactive%20Dashboard%20for%20Bank%20Customer%20Segmentation/Bank%20Customer%20Segmentation%20Analysis%20&%20Interactive%20Dashboard%20(EN).ipynb)
02. [Analysis (Jupyter Notebook in Russian)](https://github.com/Zliubov/data_analyst_projects/blob/b4607bc852c45e7afa6b121c24f069120f48adc9/Project%201:%20Interactive%20Dashboard%20for%20Bank%20Customer%20Segmentation/Bank%20Customer%20Segmentation%20Analysis%20&%20Interactive%20Dashboard%20(RU).ipynb)
03. [Presentation in Englsih](https://github.com/Zliubov/data_analyst_projects/blob/95ed5810808ed12c7ad8f32633c0577ee9689183/Project%201:%20Interactive%20Dashboard%20for%20Bank%20Customer%20Segmentation/Segmentation%20of%20the%20customers%20of%20the%20bank.pdf)
04. [Presentation in Russian](https://github.com/Zliubov/data_analyst_projects/blob/95ed5810808ed12c7ad8f32633c0577ee9689183/Project%201:%20Interactive%20Dashboard%20for%20Bank%20Customer%20Segmentation/%D0%90%D0%BD%D0%B0%D0%BB%D0%B8%D0%B7%20%D1%81%D0%B5%D0%B3%D0%BC%D0%B5%D0%BD%D1%82%D0%B0%D1%86%D0%B8%D0%B8%20%D0%BA%D0%BB%D0%B8%D0%B5%D0%BD%D1%82%D0%BE%D0%B2%20%D0%B1%D0%B0%D0%BD%D0%BA%D0%B0.pdf)
05. [Dashboard in English](https://public.tableau.com/views/Metanprom_16752050184820/MetanpromDashboard?:language=en-US&:display_count=n&:origin=viz_share_link)
06. [Dashboard in Russian](https://public.tableau.com/views/Metanprom_16752050184820/MetanpromDash?:language=en-US&:display_count=n&:origin=viz_share_link) 

#### Project steps

<details>
  <summary>See project steps</summary>
     <p>

##### **Exploratory Data Analysis**.

This stage involves visualising and summarising customer data to identify patterns and trends, and selecting appropriate characteristics for customer segmentation.

##### **Segmentation of bank customers**.

This step involves segmenting the bank's customers into no more than 4 main categories based on the number of products used and the churn rate.
It is also necessary to assess the degree of similarity between the different categories and to draw a final boundary between the categories.

##### **Statistical analysis of the data**.

In this step, statistical methods are used to further investigate and verify the segments obtained in the segmentation stage.
Testing the hypothesis of a difference in income between customers who use two banking products and those who use one.
Formulate and test the second statistical hypothesis in relation to the data presented (preliminary - are there differences in the balance of those who leave the bank and those who remain).

##### **Preparing the presentation**.

Creating of a dashboard.
Final conclusions and recommendations. 
Preparation of the research presentation for a bank manager.</p>
</details>

## 

### Project 2: A/B Test Evaluation for Recommender System (RU, ENG)<a name="project-2"></a>
This project is final project for the Data Analysis Professional Training Course at Practicum INO CPE “Yandex EdTech“ which covered a variety of topics including Python, SQL, Tableau, and business data analytics, totalling 350 hours of instruction.

#### Project Description

This project involves evaluating the results of an A/B test for a recommender system. 
The test was conducted on new users from the EU region with the goal of testing changes related to the implementation of an improved recommendation system. The technical task outlines the test name, groups, start and stop dates, audience, and expected impact. The evaluation process involves checking the correctness of the test and evaluating the test results based on specific metrics related to user actions such as product page views, product cart views, and purchases.

#### Project Language
English, Russian

#### Project files
01. [Analysis (Jupyter Notebook in English)](https://github.com/Zliubov/data_analyst_projects/blob/1e4be071159f3428e61063a2291b363b85767bbd/Project%202:%20AB%20Test%20Evaluation%20for%20Recommender%20System/AB%20Test%20Evaluation%20for%20Recommender%20System%20(EN).ipynb)
02. [Analysis (Jupyter Notebook in Russian)](https://github.com/Zliubov/data_analyst_projects/blob/1e4be071159f3428e61063a2291b363b85767bbd/Project%202:%20AB%20Test%20Evaluation%20for%20Recommender%20System/AB%20Test%20Evaluation%20for%20Recommender%20System%20(RU).ipynb)


#### Project steps

<details>
  <summary>See project steps</summary>
     <p>

##### **Exploratory Data Analysis**.

Identifying duplicates, cleaning and transforming client data, identifying patterns in the missing values (if any), processing the missing values and preparing the data for exploratory data analysis.

##### **Evaluation of the accuracy of the test**.

Evaluation of the indicators:

Evaluation of the data against the requirements of the technical task (Statement of Work). Evaluating the correctnness of all the requirements of the AB test. 
Evaluation of the timing of the test. Possible conflicts with marketing and other activities.
Evaluation of the target audience of the test. Assessment of possible overlap with a competing test, overlaps between groups. Assesmennt of the distribution and formation of the groups throughout the test.

##### **Exploratory data analysis**.

The evaluation of the questions:

Is the number of events per user evenly distributed across the samples?
How is the number of events in the samples distributed by day?
How does the conversion rate change in the funnel in the samples at different stages?
What characteristics of the data should be considered before starting A/B testing?
    
##### **Evaluating the results of A/B testing**
Evaluation of the results of the A/B test.
Statistical variance of the shares using a z-test.
    
##### **The overall conclusion**.

Conclusions on the exploratory data analysis phase and on the A/B test results you performed. A general conclusion about the validity of the test.
</p>
</details>

##

### ExtraProjects in Russian:  Various projects<a name="project-extra"></a>


#### Projects description

These projects are part of the Data Analysis Professional Training Course at Practicum INO CPE “Yandex EdTech“ which covered a variety of topics including Python, SQL, Tableau, and business data analytics, totalling 350 hours of instruction.

#### Projects Language
Russian

#### Project Moscow Catering Market Analysis

##### Project Description
Project is a data analysis project that aims to provide feedback on choosing the right location for the upcoming catering establishment in Moscow. 
The project involves analyzing a dataset of catering establishments in Moscow collected from Yandex Maps and Yandex Business. The goal is to identify interesting features of the catering market in Moscow and present the results in a concise and informative way. The project involve using various tools and visualization techniques such as matplotlib, seaborn and folium to create compelling visuals that will help the investors make informed decisions.


##### Project files
01. [Analysis (Jupyter Notebook in Russian)](https://github.com/Zliubov/data_analyst_projects/blob/640a11df052116ea14a2042ff98ed69eb557ca2e/ExtraProjects/Moscow%20Catering%20Market%20Analysis.ipynb)
02. [Presentation in Russian](https://github.com/Zliubov/data_analyst_projects/blob/3e88b9ee129282899380a0e4a4f6b4d97902b0f9/ExtraProjects/Moscow%20Catering%20Market%20Analysis%20Presentation.pdf)


#### Project Analysis of Mobile App User Behavior and A/A/B Testing for Font Change

##### Project Description

The project involves studying the behavior of mobile app users of a food products startup, specifically analyzing the sales funnel to determine how users reach the point of purchase, how many users successfully complete a purchase, and which steps cause users to get "stuck". The project also involves conducting multiple A/A tests and A/B tests to determine whether changing the fonts throughout the app will affect user behavior. The tests were conducted with a significance level of 0.05% and later at a significance level of 0.1, but there was no statistically significant difference between the groups. The conclusion is that changing the font is unlikely to produce a meaningful result, and the safer option is to move on to the next test. The positive conclusion from the tests is that the platform performs well in terms of flow distribution, as the control A/B test shows that users behave very similarly, with only around a 1% difference between the groups.
##### Project files
01. [Analysis (Jupyter Notebook in Russian)](https://github.com/Zliubov/data_analyst_projects/blob/21a3c2e146a1bac0f5a23fd8b59add877cd25c2e/ExtraProjects/AAB%20Testing%20for%20Font%20Change%20in%20an%20App.ipynb)

#### Project Hypothesis Prioritization and A/B Testing for an Online Shop

##### Project Description

The project involves conducting an A/B test for an online shop and analyzing the results. In the first part of the project, hypotheses are prioritized using the ICE and RICE frameworks based on parameters such as Reach, Impact, Confidence, and Effort. In the second part of the project, the A/B test results are analyzed by plotting cumulative revenue, average receipt, number of orders, and relative changes in these metrics for both groups. Dot plots are constructed to identify abnormal users and orders, and statistical significance is calculated for differences in average number of orders and order receipts between the groups on raw and cleaned data. Based on the results, a decision is made on whether to stop or continue the test.
##### Project files
01. [Analysis (Jupyter Notebook in Russian)](https://github.com/Zliubov/data_analyst_projects/blob/19de982c614480e18f929e6bfc6afee62c874a55/ExtraProjects/Hypothesis%20Prioritization%20and%20AB%20Testing%20for%20an%20Online%20Shop.ipynb)



