This is a report of the analysis of the health indicators associated with diabetes collected by a health-related telephone survey of over 200,000 individuals.
# Diabetes Health Indicators
![image](https://user-images.githubusercontent.com/109909855/194783189-233b9920-a96d-48dc-bc22-0ef523f3bd26.png)
# Introduction
Diabetes is a chronic disease that occurs either when the pancreas does not produce enough insulin or when the body cannot effectively use the insulin it produces. Insulin is a hormone that regulates blood glucose.
After different foods are broken down into sugars during digestion, the sugars are then released into the bloodstream. This signals the pancreas to release insulin. Insulin helps enable cells within the body to use those sugars in the bloodstream for energy. Diabetes is generally characterized by either the body not making enough insulin or being unable to use the insulin that is made as effectively as needed.
According to the World Health Organization (WHO), In 2014, 8.5% of adults aged 18 years and older had diabetes. In 2019, diabetes was the direct cause of 1.5 million deaths and 48% of all deaths due to diabetes occurred before the age of 70 years. Another 460 000 kidney disease deaths were caused by diabetes, and raised blood glucose causes around 20% of cardiovascular deaths.
While there is no cure for diabetes, early diagnosis can lead to lifestyle changes and more effective treatment. In this project, I analyzed a health-related telephone survey on diabetes collected by The Behavioural Risk Factor Surveillance System (BRFSS) from over 200,000  Americans.
# Problem Statement
From the dataset, I would analyze how different factors contribute to the risk of having diabetes. This analysis will be focused on the following factors :
* Average Body Mass Index
* Gender
* Age
* Underlying Illness and access to healthcare. 
# Data Source
The dataset used for this analysis was gotten from www.kaggle.com 
# Attributes of the data
The following are what each field in the dataset means:
* Diabetes - 0 = no diabetes 1 = prediabetes 2 = diabetes
* High Blood Pressure - 0 = no high blood pressure 1 = high blood pressure
* High Cholesterol - 0 = no high cholesterol 1 = high cholesterol
* Cholesterol Check - 0 = no cholesterol check in 5 years 1 = yes cholesterol check in 5 years
* BMI - Body Mass Index
* Smoker -  smoked at least 100 cigarettes in your entire life? [Note: 5 packs = 100 cigarettes] 0 = no 1 = yes
* Stroke - had a stroke. 0 = no 1 = yes
* Heart disease or heart attack - coronary heart disease (CHD) or myocardial infarction (MI) 0 = no 1 = yes
* Physical activity - physical activity in past 30 days - not including job 0 = no 1 = yes
* Fruits - Consume Fruit 1 or more times per day 0 = no 1 = yes
* Veggies - Consume Vegetables 1 or more times per day 0 = no 1 = yes
* Heavy Alcohol Consumption - Heavy drinkers (adult men having more than 14 drinks per week and adult women having more than 7 drinks per week) 0 = no 1 = yes
* Any Healthcare - Have any kind of health care coverage, including health insurance, prepaid plans such as HMO, etc. 0 = no 1 = yes
* No doctor because of cost - Was there a time in the past 12 months when you needed to see a doctor but could not because of cost? 0 = no 1 = yes
* General Health - Would you say that in general your health is: scale 1-5 1 = excellent 2 = very good 3 = good 4 = fair 5 = poor
* Mental Health - Now thinking about your mental health, which includes stress, depression, and problems with emotions, for how many days during the past 30 days.
* Physical Health - Now thinking about your physical health, which includes physical illness and injury, for how many days during the past 30 days.
* Difficulty working - Now thinking about your physical health, which includes physical illness and injury, for how many days during the past 30 days.
* Sex - 0 = female 1 = male
* Age - 13-level age category (_AGEG5YR see codebook) 1 = 18-24 9 = 60-64 13 = 80 or older
* Education - Education level (EDUCA see codebook) scale 1-6) 1 = Never attended school or only kindergarten 2 = Grades 1 through 8
* Income - Income scale (INCOME2 see codebook) (scale 1-8) 1 = less than $10,000 5 = less than $35,000 8 = $75,000 or more
# Data Cleaning in Microsoft Excel
The dataset was checked for duplicate values, 23899 duplicate values were found and removed and 229,781 unique values remained.
![diabetes duplicate](https://user-images.githubusercontent.com/109909855/194786316-3ab3a8c3-17fc-4427-927c-85c683f5d99b.JPG)
The dataset was checked for misspellings and null values, No misspelling or null value was found.
Column names were renamed for clarity.
![diabetes spell check](https://user-images.githubusercontent.com/109909855/194786604-f0d4075a-8d2d-425e-9cbe-fc61fb00135b.JPG)
# Visualization
Visualization for this project was done with MICROSOFT EXCEL.
![Final Diabetes Dashboard](https://user-images.githubusercontent.com/109909855/225300527-16812347-3bd3-4cbe-a6e4-f5ba53527a3f.JPG)

# Insights
* From the dataset, it was deduced that people with a higher average Body Mass Index (BMI) were at a higher risk of having diabetes. 
![Final Average BMI by condition picture](https://user-images.githubusercontent.com/109909855/225301547-edc630f5-0e50-4da3-972e-4b32006784f5.JPG)


People with diabetes had the highest average BMI - 31.96, followed by prediabetic patients with an average BMI of 30.766. Non-diabetic patients had an average of 28.031(the lowest). 
* A total number of 35,097 patients reported that they were diabetic, Out of this total, 16752 of them were males accounting for 47.73%. 18345 of them were females accounting for 52.27%.
![final diabetes - gender by condition](https://user-images.githubusercontent.com/109909855/225302304-747b1a5a-de4a-4ca6-8b4c-e3a4f4d305b0.JPG)

* Analysis of this dataset showed that diabetes is more common in older people.
![image](https://user-images.githubusercontent.com/109909855/195997636-a62d373d-ec08-4ae4-a630-7816facef7d0.png)
* Underlying illnesses of diabetic and non diabetic patients were also analyzed, high cholesterol, high blood pressure, stroke and heart disease were analyzed.


![Capture](https://user-images.githubusercontent.com/109909855/225304813-d443c010-c5c3-4e42-94ca-60ba2744b947.JPG)


As seen above, underlying illnesses were spread across the three categories, non-diabetic patients had the highest occurrence of high blood pressure and high cholesterol, this shows that the underlying illnesses mentioned above are not a direct cause of diabetes in people.

* Access to healthcare was the last metric used in this analysis. As shown below, proper access to healthcare was associated with no diabetes.
* 
![Access to healthcare by condition - Final dataset](https://user-images.githubusercontent.com/109909855/225303997-84bdaba8-cbbe-4a2f-aecd-12f62452624a.JPG)

