## Selected Work in Data Science, AI, and Research

---
### Machine Learning & AI

[Optimization of Renewable Energy to Supply Chains](https://blog.paperspace.com/optimizing-the-integration-of-renewable-energy-to-our-supply-chains/)
Identifying effective renewable energy solutions is challenging due to complex supply chains and variable outputs. I used Gurobi to model combinations of renewable energy options under cost constraints, optimizing allocations to maximize energy production while minimizing investment, providing realistic projections and supporting broader consumer adoption.
Real-world scenarios:
Urban traffic management: Modeling traffic flow probabilities in city networks where overall congestion depends on both signal timing choices and inherent variability in traffic volumes throughout the day.
<img src="images/optimization.png?raw=true" />

---
[A Bayesian Approach to Supplier Optimization](https://medium.com/@oefeleinerin/a-bayesian-approach-to-supplier-optimization-9efb2e2c9a58) 
Optimized supplier selection and manufacturing output using Bayesian modeling to account for variability in supplier yields and production quality. Leveraged PyMC to model supplier performance with hyperpriors and empirical priors, estimating how much product could be successfully manufactured under current supplier conditions. Performed scenario analysis to identify top-performing suppliers, reducing waste from lost product by 68% and providing actionable insights for supply chain decision-making.

<img src="images/BFMI.png?raw=true" />

---
[Love Island's Love Algorithm](https://blog.paperspace.com/winning-hearts-love-islands-love-algorithm/)
Behavior in networked systems is often difficult to predict due to complex relationships between entities. I applied Graph Convolutional Networks to model these relationships within network-focused software products, uncovering patterns that can help predict user behavior and guide product decisions.
<img src="images/network.png?raw=true" />

---
[Personalizing the Customer Experience with Reinforcement Learning](https://medium.com/@oefeleinerin/smarter-engagement-lower-churn-the-role-of-reinforcement-learning-in-personalizing-the-customer-82580b39c2f2)
Implemented a **Reinforcement Learning (RL)** solution using **SARSA(λ)** and tile coding to reduce user churn on an online tax filing platform. Modeled user interactions as states, interventions as actions, and retention as rewards. The RL agent learned to select optimal actions, such as offering a Tax Professional, personalized incentives, or proactive support, maximizing retention while minimizing unnecessary interventions.  
<img src="images/SARSA.png?raw=true" />

Key outcomes:  
- Improved early churn detection by analyzing action-value functions.  
- Identified interventions most likely to prevent churn, guiding personalized customer experiences.  
- Demonstrated how RL can dynamically optimize decisions in a complex, multi-factor environment.  

---
[Bayes for Business](https://medium.com/@oefeleinerin/bridging-the-gap-leveraging-machine-learning-and-human-expertise-for-smarter-marketing-6047774b5ef6)
Bayesian probabilistic models are increasingly being adopted in marketing analytics as a powerful alternative to traditional single-point estimation methods. By integrating prior knowledge, accounting for uncertainty, and modeling complex real-world dynamics, these models provide a richer, more flexible framework for understanding customer behavior and channel performance. In my project, I applied Bayesian attribution to optimize marketing spend across channels, yielding actionable insights and guiding data-informed decision-making.
 - The model fosters business buy-in by integrating domain expertise, actively involving stakeholders in the modeling process.
 - Quantifies channel impact by attributing customer acquisition to each marketing channel directly. - Shows how to allocate funds to maximize customer acquisition.
<img src="images/posterior_predictive_plot.png?raw=true" />

---

### Data Engineering & Pipelines

[Azure Real Estate Rental Data Pipeline](https://github.com/yourusername/real-estate-pipeline)
Built a data pipeline to collect U.S. rental listings automatically in Azure, tracking how long homes take to be rented across zip codes. Analyzed features such as number of bedrooms, location, and amenities to identify what drives faster rentals, providing actionable insights for investors and property managers.

---
[Amazon Resale Ticket Pricing Pipeline](https://github.com/yourusername/ticket-pricing-pipeline)
Developed a data pipeline in AWS to automatically collect pricing data on resale tickets from multiple platforms. Processed and stored structured data to analyze trends, identify pricing patterns, and assess market dynamics. Insights from this pipeline inform pricing strategies and highlight factors that drive ticket value in secondary markets.

---
[Tiny House Nation the SQL](/sample_page)
What drives consumer behavior? Using tiny home listing data, this project explores whether lifestyle preference or economic factors drive consumers to adopt a tiny home lifestyle. In this project, I build a full data pipeline using Scrapy and Selenium to scrape U.S. tiny house listings. To understand spatial trends, I applied the Local Moran’s I statistic to identify pricing clusters. Users can visualize where pricing drives tiny home living using a Dash application, productionized using Docker and deployed on GCP for scalable, interactive exploration.
<img src="images/dummy_thumbnail.jpg?raw=true"/>

---
[Building a Career Pipeline](https://github.com/eoefelein/Beautiful_Soup_Mongo_xlsxwriter)
Built a data pipeline to extract job posting data in the tech sector from Austin’s Craigslist, storing it in an unstructured MongoDB database and exporting to Microsoft Excel at a scheduled time every day.
<img src="images/dummy_thumbnail.jpg?raw=true"/>

---
### Workshops & Education

[WiDSAI Workshops](https://github.com/eoefelein/WiDSAI_Python_Workshop)
Created and facilitated a hands-on Python workshop (WiDSAI) in Google Colab, allowing learners to explore real datasets, practice data analysis, and build coding skills independently.

<img src="images/WiDSAI_Meetup.jpeg?raw=true" />

[View code on Colab](https://colab.research.google.com/drive/1dF7hj7BjNH5RWcGKskdJRYkkdq8WDDiL?usp=sharing)

### Academic Research

[SHAPing the Future of Electrocatalysts](https://pubs.acs.org/doi/10.1021/acsmaterialslett.4c00544)
Machine learning models are often difficult to interpret, making it challenging for researchers to understand which electrocatalyst material properties drive performance. This project demonstrates how SHAP empowers researchers with identifying promising candidates, near, but not identical to, known electrocatalysts, demonstrating how interpretable model guide decision-making and scientific discovery.

[View code on GitHub](https://github.com/eoefelein/Understanding-Performance-Trends-Using-Machine-Learning)

---
[Winning with Probability](https://medium.com/data-science/magic-the-gathering-arena-winning-with-probability-b71f363e0ce2)
Modeled outcomes in environments where user decisions interact with probabilistic events and rewards. By applying probabilistic analysis to sequential decision-making scenarios, I demonstrated how strategy and chance combine to shape outcomes, enabling insights into behavior, engagement, and potential optimization of rules or incentives.
Real-world scenarios:
Education / adaptive learning platforms: Modeling student success probabilities in platforms where learning outcomes depend on both student choices (e.g., problem-solving paths) and inherent uncertainty in mastery or question difficulty.

---
[LASSO](https://medium.com/data-science/lasso-increases-the-interpretability-and-accuracy-of-linear-models-c1b340561c10)
This article shows how LASSO uses an L1 penalty to perform feature selection and reduce collinearity, building sparser, more interpretable models. Visualizations of constraint regions and contours illustrate why some coefficients shrink to zero, giving an intuitive, math-backed understanding of LASSO.

<img src="images/lasso.jpeg?raw=true" />

[View code on GitHub](https://github.com/edkrueger/lasso-demo) 

---
