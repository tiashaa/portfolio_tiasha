## Research Methodology & Technical Skills 
- **Programming & Development:** Python (TensorFlow, Scikit-learn, Pandas, NumPy, Matplotlib, Seaborn), 
SQL, R 
- **Machine Learning & AI:** Supervised/Unsupervised Learning, Neural Networks, NLP & Sentiment Analysis, 
Time Series Forecasting, Clustering, Image Processing, Explainable AI (XAI).
- **Statistical Methods:** ARIMA/ARMA/SARIMAX, Regression Analysis (Multinomial Logistic, Proportional 
Odds), Min-Max Normalization, Hypothesis Testing, Cross-Sectional Study Design
- **Data Engineering & Cloud:** ETL Pipelines, AWS (S3, Lambda), Data Extraction & Transformation, 
Automated Reporting Systems 
- **Visualization & BI Tools:** Tableau, Power BI, Matplotlib, Seaborn
- **Research Domains:** Telecommunications Analytics, Supply chain analytics, Air Quality Forecasting, Public 
Health Data Analysis, Cybersecurity (Web Vulnerability Assessment) 

## Ongoing Research 
- Explainable and Statistically Validated Bangla Sentiment Analysis: A Comparative Study of Classical, Deep 
Learning, and Transformer Models. [submitted to ICCA 2026, click here](https://colab.research.google.com/drive/1fMUrBPIBXx3RCSEfh7EME1Rm7dLuuVHf?usp=sharing) 
- Electricity Demand forecasting for Bangladesh with hybrid classical statistical and machine learning model. 
- Sentiment Analysis on Multilingual Customer Reviews of Mobile Telecommunication Services Using 
Machine Learning and Deep Learning techniques. 
- Determinants of Menstrual Hygiene Management Among Women of Reproductive Age in Bangladesh: A 
Cross-Sectional Study Comparing Multinomial Logistic and Proportional Odds Regression Models Using 
MICS Data(working paper)


## Work Experience
**Supply Chain Performance Management Expert @ Grameenphone - Finance (_Aug 2024 - Present_)**
- Inventory Optimization Framework for Telecom Using Demand Forecasting and Inventory Classification 
- Assemble, Analyze and organize large data generated from system logs.  
- Visualize data on power BI Dashboards 
- Automation of reports, which are needed to circulate regularly. 
- Analyze data to forecast savings, helping with data driven decision making 
- Developing Machine Learning models to forecast business trend over time.
  

**Senior Engineer @ Edotco Group Limited - Data Science & Analytics (_Mar 2024 - Aug 2024_)**
- Using cloud solutions(AWS, S3, Lambda) for data fetching and analysis, EDA for global platform 
- Data visualization to show trends, important features using POWER BI, Machine Learning Engineering to 
do predictions  
- Collaborating with the data architects, engineers,analysts, and scientists of different countries. 
- Image processing to automate billing systems.
  
**Specialist @ Robi Axiata Limited - Assurance & Fulfilment (_July 2022 - Mar 2024_)**
- Assemble, analyze, and organize large, complex data with Analytical and problem solving abilities.  
- Real life clustering and prediction using machine learning models. 
- Data visualization to show trends, important features using TABLEAU and using Machine Learning 
Engineering to do predictions  
- Extraction, transformation, and loading of data using SQL, Python along with Application development and 
tools management.

## Projects
### Customer Churn Prediction
[Churn Prediction](https://colab.research.google.com/drive/1VJySmmj3wHxRfs_6pzb5F0KYK1OD0wyC?usp=sharing)  
This project walks through a full machine learning pipeline using the Telecommunication dataset. It begins with data exploration and preprocessing, including handling missing values, converting data types, encoding categorical variables, and scaling numerical features. Exploratory analysis reveals that customers with month-to-month contracts, higher monthly charges, or fiber optic internet are more likely to churn, while long-tenure customers and those with bundled services are more likely to stay. Various classification models like logistic regression, random forest, and gradient boosting are trained and evaluated using accuracy, F1-score, and ROC-AUC, achieving strong performance. The notebook highlights the value of churn prediction in identifying high-risk customers and enabling businesses to take proactive retention measures.  

<div style="display: flex; flex-wrap: wrap; gap: 10px;">
  <img src="https://github.com/user-attachments/assets/86d66060-516d-4cb0-bc14-964845a34902" width="500"/>
  <img src="https://github.com/user-attachments/assets/4094d213-b2a0-4971-aa40-65de3613e6a7" width="500"/>
  <img src="https://github.com/user-attachments/assets/6a7d5503-7694-4c9a-8f0c-8bc76bad33e7" width="500"/>
</div>  
  <br>
  
### Time Series Forecasting
[Beijing Air Pollution Prediction](https://colab.research.google.com/drive/1hww8gPPFgfT0I5in6KNDrx-CK1eg-gDd?usp=sharing)  
It is a complete deep learning-based approach to time series forecasting using an LSTM model. The dataset is loaded and processed by converting the datetime column to a proper datetime index, handling missing values with forward fill, and ensuring the data is in a continuous time series format. It visualizes trends and seasonality in the data to better understand its structure. The values are normalized using MinMaxScaler to scale features between 0 and 1, which is critical for stable LSTM training. The data is then split into training and testing sets without shuffling, and a custom function is defined to convert the time series into supervised learning format by creating sequences of past values as input to predict the next value. An LSTM model is constructed using Keras Sequential API with LSTM and Dense layers, compiled with the mean_squared_error loss and adam optimizer. The model is trained using model.fit(), and predictions are made on the test set. The predicted results are compared visually and evaluated using mean_squared_error. Finally, the model is used for multi-step future forecasting by iteratively feeding back predicted values, showcasing the model's ability to forecast beyond the available data range.


<div style="display: flex; flex-wrap: wrap; gap: 10px;">
  <img src="https://github.com/user-attachments/assets/ff63451f-4752-4878-9e33-e08da11b1527" width="500"/>
  <img src="https://github.com/user-attachments/assets/956e7ced-c56c-4d51-8f5e-6ee8474d8dc0" width="500" />
</div>  
<br>
    
### Bangla & English Image to Text
[Image to Text](https://colab.research.google.com/drive/1VJySmmj3wHxRfs_6pzb5F0KYK1OD0wyC?usp=sharing)

This project shows how to perform Optical Character Recognition (OCR) on mixed Bengali and English text using pytesseract, a Python wrapper for Tesseract OCR. It guides through setting up Bengali language support by installing the ben.traineddata model, configuring Tesseract to recognize Bengali (lang='ben') as well as English, and processing sample book-page images. The workflow includes preprocessing steps like image cleaning and setting up the correct tessdata directory, followed by invoking pytesseract.image_to_string() to extract multilingual text from input images. It's an applied example of extending Tesseract’s default English OCR to handle Bengali script effectively.   

<br>

    
### Machine Learning Algorithms Using Python
[Machine Learning Algorithms](https://www.kaggle.com/work/collections/16287124?privacy=public&owner=owns)
This is a collection of python codes of making machine learning algorithms from scratch for learning purpose.    

<br>
    
### Web Scraping: Hourly Weather Data for Bangladesh
[Hourly Weather Data for Bangladesh](https://colab.research.google.com/drive/1TftZPDQ4bkrb4Ygg7ke1Bm56MPejJxTo?usp=sharing)  
This Colab notebook focuses on web scraping and data visualization related to electricity imports and fuel sources. It uses tools like requests and BeautifulSoup to extract data on electricity imports from neighboring countries such as India and Nepal, as well as the contributions of different fuel sources like gas, coal, hydro, and solar. After cleaning and organizing the data, the notebook visualizes trends over time using line and bar charts to highlight import volumes and the share of various energy sources. These visualizations provide insights into energy dependency patterns, seasonal shifts in fuel usage, and the role of each country in electricity imports.  
<div style="display: flex; flex-wrap: wrap; gap: 10px;">
<img src="https://github.com/user-attachments/assets/5fcfcb8e-3c2b-4f7f-b1c1-3951ea19006a" width="500" height = "200" />
<img src="https://github.com/user-attachments/assets/a05a326e-4b41-46f1-bd2a-f2c18d20df70" width="500" height = "200"/>

</div>

<br>

    

### Tableau Development
[The Rise of Android in 2008-14](https://public.tableau.com/app/profile/hridita.tiasha/viz/TheRiseofAndroid2008-14_17535284176230/TheRiseofAndroidin2008-14)


<div style="display: flex; flex-wrap: wrap; gap: 10px;">
  <img src="https://github.com/user-attachments/assets/906c6206-5d57-4003-a353-b246aecb69e8" width="500"/>
  <img src="https://github.com/user-attachments/assets/daed2800-3970-4f57-a41f-bed80864017e" width="500" />

</div>

<br>
    
[Bangladesh](https://public.tableau.com/app/profile/hridita.tiasha/viz/Bangladesh_17535288902940/Dashboard1)
<div style="display: flex; flex-wrap: wrap; gap: 10px;">
  <img src="https://github.com/user-attachments/assets/d367eef6-8938-437d-b191-29494cf5a42d" width="300" />
</div>

<br>
    

## Certifications  
- [Hackerrank: SQL Intermidiate](https://www.hackerrank.com/certificates/d29b94a7b6d3)				       		
- [Hackerrank: Python Basic](https://www.hackerrank.com/certificates/4c2874f1a4b7)
<br>

    
## Competitions  
- Runners up at the Category LFR in Essonance(2019)
- Runners up at the Category LFR in Mecceleration(2019)	 			        		
	



## Education
- M.Sc, Data Science & analytics  | East West University (_Ongoing_)	
- B.Sc, Computer Science & Engineering  | Islamic University of Technology (_May 2022_)			       		
- H.S.C, Science			| Holy Cross College (_June 2017_)	 			        	
- S.S.C, Science 			| Jhikargacha GOVT ML High School (_June 2015_)
