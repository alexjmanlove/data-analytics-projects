# Data Analytics Internship Projects

This is a collection of three data science and econometrics projects I developed while working as a data insight analyst intern for Dunelm Group in 2021.

**Key technologies**: `Python`, `SQL`, `pandas`, `NumPy`, `Microsoft Excel`.

## 1. TV Marketing Campaign Analysis   

### **Context**
>This project in econometrics and causal inference aimed to measure the revenue uplift after an advertising campaign. 

### **Challenges**
>This analysis was complicated by the COVID lockdowns that occured in the UK. In particular the advertising campaign launched on the same day that the third lockdown resstrictions were relaxed. Therefore the task was not simply to measure the uplift, but also to measure the uplift on top of what would already have resulted due to end of lockdown.

### **Solution**
>In Python leveraging the package PyCausalInference we were able to apply a Bayesian causal inference model to help estimate the causal effect of the campaign on revenue uplift over key product categories, using similar product categories as a control group. The project made use of historical data to train and test the model, and the key learnings were used to inform future marketing strategies. 

### **Preview**
>![image](https://user-images.githubusercontent.com/79708390/213026884-6718aa08-5aa4-49fe-bd76-9af913a209ba.png)
>![image](https://user-images.githubusercontent.com/79708390/213028968-17fc68f8-4b84-4238-9c45-718d33610ca8.png)


## 2. Brand Perception vs Market Share Analysis

### **Context**
>This project in analytics sought to cross reference data from two external sources in order to identify trends, patterns and relationships between customer's perception of the brand and the organisation's actual market share. 

### **Challenges**
>As a result of the data being sourced from two different external providers, much cleaning and preparation had to be done before the data could be prepared and analysed. Use of fairly involved `SQL` joins was necessary, as well as lots of manual reformatting and tidying using `pandas` and `Excel`.

### **Solution**
>In the end I was able to visaulise the data clearly and provide actionable insights for key stakeholders. 

### **Preview**
>![image](https://user-images.githubusercontent.com/79708390/213029184-26ad7901-2701-4aee-a5b1-fde8a0524866.png)
>![image](https://user-images.githubusercontent.com/79708390/213031234-5f5f18a3-bee5-4176-87f9-1d241ac46888.png)


## 3. Refit Revenue Analysis 

### **Context**
>Similarly to project 1, the organisation launched a series of store refits and were curious to find out what the causal effect of these refits was on gross transaction value and volume. 

### **Challenges**
>Unlike the previous case, it was not clear or easy for us to compare like for like on treated vs control categories. Data from 170 stores was available, but many of these were in different parts of the country and went into lockdown at different times, making it difficult for us to properly formulate a controlled experiment and account for confounding factors. 

### **Solution**
>We performed K-means clustering on the time series of revenue data over all these 170 stores, to perform unsupervised clustering. In the end the approach was able to determine clusters of stores whose behaviour was similar. On this basis I was then able to apply a similar Bayesian causal inference modelling approach to quantify the uplift in revenue due to store refits. 

### **Preview**
>![image](https://user-images.githubusercontent.com/79708390/213028126-bd5a6c38-3cbe-454a-b0d1-b542e86f73bb.png)
