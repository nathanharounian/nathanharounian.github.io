# Data Scientist

#### Technical Skills: Python, SQL, Salesforce, Tableau, R, ShinyApp, Statistical Analysis, Data Visualization, Model Building, MATLAB

## Education
- B.A., Statistics | University of California, Berkeley (_May 2024_)            		

## Work Experience
**Data Analyst @ Transform Health (_November 2024 - Present_)**
- Manage over 3 projects and create work plans, workflows and SOPs for internal and external use, including a 50+ page SOP for an audit process of the 3-year Incentive Payment Program with over $1.5B in funding from DHCS to Medi-Cal managed care plans
- Create over 16 maps, bar graphs, and circle charts in Tableau to summarize $86M+ in funding awarded from Global Health Plan client to California providers and health organizations through CalAIM in yearly report for C-suite executives
- Serve on Executive MIS/Ops Team to plan and implement company-wide policies in AI-use and file management; triage MIS help desk tickets and provide technical support to staff members; interview and hire IT vendor to enhance internal security operations
- Consult project leads and collaborate with MIS team to create new objects, records, layouts and pages in Salesforce for various new and current projects of differing scopes of work and CRM needs
- Create an online document hub in SharePoint, train and onboard over 60 health plan and county agency partners in over 12 counties to collaborate on policy and procedure documents; track data of users, create client-branded dashboards in Excel, and report metrics directly to the CEO of the client

**Analyst @ S&T Fraternity Management (_May 2024 - Present_)**
- Analyze rent prices and room layouts to meet income standards of $41,000+ set by the executive committee board.
- Recruit and manage 25+ tenants; collect rent, report any repair requests, and communicate upcoming deadlines and events
- Work with S&T Leasing Manager and Board of Trustees to navigate deficits and losses over the years, yielding net 0 debt.

**Head Teaching Assistant @ UC Berkeley College of Computing, Data Science, and Society (_August 2022 - December 2023_)**
- Taught machine learning concepts (SQL, Python, PyTorch) to 35+ undergraduates in theory and lab environments
- Led weekly discussion and office hours, contributed to course content, exam creation, and course administration
- Managed relationships with stakeholders via technical and non-technical weekly emails to create educational pathways for 250+ students

**Data Analytics Researcher @ UC Berkeley Statistics Department (_September 2022- May 2023_)**
- Deployed multiple solutions to streamline data analysis and data visualization, increasing analysis efficiency by 10x
- Independently managed and analyzed multiple datasets (10M+ feature values) in R Studio
- Collaborated with research partners, designing and conducting research studies through supervised machine learning to evaluate, predict, and report consumption of information on social media platforms

## Projects
### Predicting Cancer Survival Status

![Gene](/assets/img/cancer.jpg)

[PDF Report](https://github.com/nathanharounian/Cancer-Survival-RF-Model/blob/main/cancer-survival-genes-rf-model.pdf)
| [GitHub Repository](https://github.com/nathanharounian/Cancer-Survival-RF-Model)

Using data from The Cancer Genome Atlas (TCGA), conducted EDA to find a good classifying threshold between ‘high’ and ‘low’ survival. Then, conducted data cleaning by either imputing or removing NA values. Finally, found the most important covariates (genes) through PCA, fit a Random Forest using 10-fold Cross Validation, resulting in a final classifying model with 91% test set accuracy and a Kappa Statistic of 67%.

### CCAO Housing Price Model

![Housing Prices](/assets/img/house_prices.jpg)

[PDF Report](https://github.com/nathanharounian/CCAO-Housing-Price-MLR-Model/blob/main/proj1b.ipynb)
| [GitHub Repository](https://github.com/nathanharounian/CCAO-Housing-Price-MLR-Model)

A linear model using multiple features from the Cook County Assessor’s Office large housing data (204792 observations and 62 features in training data, 68264 observations and 61 features in test data) after exploring the data, refining features, creating new features, and transforming select features) to predict housing prices. Error of model analyzed and improved using Cross Validation on training and test sets.

### Beyoncé Lyric Analysis Application

![Beyoncé Knowles-Carter](/assets/img/beyonce.webp)

[Application](https://nathan-harounian.shinyapps.io/beyonce/)
| [GitHub Repository](https://github.com/nathanharounian/Lyric-Sentiment-Analysis)

Published **ShinyApp** which conducts varying song lyric analysis from azlyrics.com (data cleaning and text mining with Regex). Types of analysis include a word frequency analysis, classic sentiment analysis, sentiment trajectory analysis, and sentiment contribution analysis (all of which display unique bar plots and histograms). The app allows you to pick a specific album of an artist from which to conduct the analysis, or the ability to choose all albums or per album.

### Retirement Withdrawal Simulation

![Retirement](/assets/img/retirement.jpg)

[Application](https://nathan-harounian.shinyapps.io/RetirementPortfolioBalance/)
| [GitHub Repository](https://github.com/nathanharounian/Retirement-Withdrawal-Simulator)

Published **ShinyApp** in **R** which simulates retirement portfolio balances until the age of 100 using indicators such as initial portfolio amount, retirement age, withdrawal rate; additional inputs such as average annual return and volatility rates and average inflation and volatility rates were modeled to follow a normal distribution for the purposes of the project. These indicators then produce a detailed line plot where each line on the plot represents a single simulation with highlighted lines for quartiles and the average, followed by a table of summary statistics.

### Email Spam Classifier Model

![Email Spam](/assets/img/email_spam.png)

[PDF Report](https://github.com/nathanharounian/Email-Spam-Classifier-Model/blob/main/Email%20Classifier.pdf)
| [GitHub Repository](https://github.com/nathanharounian/Email-Spam-Classifier-Model/tree/main)

Built a Logistic Regression Model to classify spam emails for detection purposes in **Python** and **JupyterNotebook**. Model built using email data and many engineered features using **Regex** and other functions written from scratch.

### GLM for Predicting Managerial Salaries

![Salary](/assets/img/salary.png)

[PDF Report](https://github.com/nathanharounian/GLM-for-Prediciting-Managerial-Salaries/blob/main/Predicting-Managerial-Salaries-Modeling-Report.pdf)
| [GitHub Repository](https://github.com/nathanharounian/GLM-for-Prediciting-Managerial-Salaries)

Using **R**, defined a GLM with a Gamma likelihood due to positive-valued outcome variable Salary. Performed model selection using AIC — a function of the KL-Divergence — and BIC criterion metrics, using the best covariates for the model to predict the log of managerial salaries. Checked the validity of the model using a Q-Q plot for the normality assumption, a scale-location plot to check for homoscedasticity, and a residuals vs leverage plot to locate potential influential points using Cook’s distance, as well as a leverage vs studentized residuals plot to look for points with high leverage. Reported RMSE of the held-out test set was about 0.466.


