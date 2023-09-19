# Cyber Crime Cases in Malaysia 

## Abstract
Cybercrime has emerged as a major global problem, posing threats to individuals, organisations, and the nation's cybersecurity. This summary presents an overview of cybercrime in Malaysia, including cyber harassment, content-related offences, intrusion attempts, fraud, malicious code, vulnerability reports, denial of service, and spam. The research investigates the incidence, trends, strategies, and consequences of various cybercrimes, emphasising emerging tactics utilised by Malaysian cybercriminals. Increased cyber harassment events, sophisticated attack attempts on important infrastructure, and economic losses due to cyber fraud are among the key findings. The report also examines the government's attempts to combat cybercrime through legal measures, law enforcement activities, and public awareness initiatives, giving policymakers and cybersecurity experts with insights into how to successfully handle these risks.

## Introduction
Cybercrime in Malaysia has emerged as a serious and developing menace in the digital era. With the fast development of internet access and technology use, the country has seen a surge in many types of cyber dangers, such as online fraud, hacking, identity theft, and cyberbullying. Malaysian authorities have taken attempts to address these difficulties through legislative measures and law enforcement initiatives, but cybercriminal activities continue to be a major concern, posing hazards to individuals, organisations, and the nation's broader cybersecurity environment.

## Methodology

### Model

#### 1. Data Preprocessing
Data preprocessing is a fundamental requirement for conducting reliable data analyses, especially when dealing with intricate building operations and potential data quality issues. It encompasses a range of methods aimed at improving the integrity of raw data, including the identification and handling of outliers and missing values (Cheng Fan, Meiling Chen, Xinghua Wang, Jiayuan Wang & Bufu Huang, 2021).

#### 2. Data Visualization
Data visualization involves the creation and utilization of computer-generated graphical depictions of data, encompassing the design and development of such representations. It serves as a powerful means to visually present data stemming from diverse origins, offering decision-makers the ability to perceive analytics in a visual format, facilitating data comprehension, pattern recognition, and informed decision-making (Matthew N O Sadiku, Adebowale E. Shadare, Sarhan M. Musa, Cajetan Akujuobi & Roy G Perry, 2016).

#### 3. Data Classification
Data classification refers to the deliberate decision-making process of assigning a sensitivity level to data during its creation, modification, augmentation, storage, or transmission. The classification of intellectual property should be driven by the degree of control and security required for the data, as well as its assessed value as a business asset (Craig Wright, 2008).

#### 4. Exploratory Data Analysis (EDA)
Exploratory data analysis (EDA) stands as a crucial initial phase in any research investigation. Its primary objective involves scrutinizing the data for patterns, distributions, outliers, and irregularities, thereby guiding focused hypothesis testing. Additionally, EDA equips researchers with visualization tools to facilitate the comprehension and representation of data, aiding in the identification of inherent patterns, and aiding the analyst in recognizing natural data patterns (Matthieu Komorowski, Dominic C. Marshall, Justin D Salciccioli & Yves Crutain, 2016).

#### 5. Model Evaluation
Assessing the effectiveness of a developed predictive model, commonly referred to as model evaluation, holds a pivotal role within the realm of machine learning. This significance arises from the fact that the value of the model predominantly hinges on its estimated predictive capabilities. Model evaluation techniques not only serve as crucial tools for gauging the effectiveness of a trained model but also contribute significantly to the process of building the model in the first instance (Amin Zollanvari, 2023).

### Steps

#### 1. Excel Reader
This node reads data from an Excel file. It is the starting point of the procedure, where it will import the dataset.

![excel reader](https://github.com/nicaaaaaaa/codeless-data-science-fundamental-2023-FTU-x-UMK/assets/93868117/d42d698f-03b1-4fc0-8349-1efbf314e53e)

#### 2. Column Filter
This node allows to choose certain columns or properties from the dataset. You may use it to remove extraneous columns from your analysis or modelling.

![column filter](https://github.com/nicaaaaaaa/codeless-data-science-fundamental-2023-FTU-x-UMK/assets/93868117/c50932be-8a9a-459b-a307-099037d0ea9f)

#### 3. Color Manager
The Colour Manager node is often used for visualisations. It lets you to apply colours to categories or groupings of data, which may be useful for constructing aesthetically pleasing and informative charts and plots.

![color manager](https://github.com/nicaaaaaaa/codeless-data-science-fundamental-2023-FTU-x-UMK/assets/93868117/b53ba784-31ad-4581-9d48-0d474eeb8cb6)

#### 4. Pie/Donut Chart
These nodes are used to generate pie or donut charts, which are useful for visualising the distribution of categorical data or displaying the proportion of distinct categories within a dataset.

![pie chart](https://github.com/nicaaaaaaa/codeless-data-science-fundamental-2023-FTU-x-UMK/assets/93868117/6eeff48f-6b1f-4195-a0ed-4b46792a19a5)

#### 5. Partitioning 
Partitioning nodes divide your dataset into training and testing portions. This is essential for training and assessing your machine learning model. It guarantees that you have a different dataset to test the performance of the model. In this workflow, the nodes divide 70% for training and 30% for testing.

![partitioning](https://github.com/nicaaaaaaa/codeless-data-science-fundamental-2023-FTU-x-UMK/assets/93868117/5f6dabc8-e3fa-459d-84aa-4a1479e0c0c6)

#### 6. Bar Chart
You customise the "Bar Chart" node by providing which column(s) from your data table you wish to use for the categories and, optionally, the values to be shown on the y-axis.

![bar chart](https://github.com/nicaaaaaaa/codeless-data-science-fundamental-2023-FTU-x-UMK/assets/93868117/dcfe80af-1e7a-4adb-888c-eae7a47ad5ac)

#### 7. Decision Tree
The Decision Tree node is where you train a machine learning model, especially a decision tree classifier, using your training data. Decision trees are used for categorization problems and produce predictions based on a tree-like structure of decision rules. This workflow use decision tree learner and decision tree predictor to predict the expected number of cases in the coming months and the most common one.

![decision tree](https://github.com/nicaaaaaaa/codeless-data-science-fundamental-2023-FTU-x-UMK/assets/93868117/ed7afc81-58b9-468c-a01f-636bb933c178)

#### 8. Statistics
The Statistics node computes summary statistics for your data. It can give insights into the central tendency, variability, and dispersion of your data.

![statistics](https://github.com/nicaaaaaaa/codeless-data-science-fundamental-2023-FTU-x-UMK/assets/93868117/29f58685-6a53-40e7-adf5-61a032c1cee2)

#### 9. Scatter Matrix (local)
This is another node for making scatter plots, and it may have unique local visualisation settings or goals.

![scatter matrix (local)](https://github.com/nicaaaaaaa/codeless-data-science-fundamental-2023-FTU-x-UMK/assets/93868117/58aaa3d6-04a8-4665-acae-ac66bc343aa1)

#### 10. Naive Bayes
The Naive Bayes node is where you train a Naive Bayes classifier on your training data. Naive Bayes is a probabilistic classification technique that is used for applications such as text categorization and spam detection. This workflow use naive bayes learner and naive bayes predictor to predict high-risk month.

![naive bayes](https://github.com/nicaaaaaaa/codeless-data-science-fundamental-2023-FTU-x-UMK/assets/93868117/6688ecfe-edca-4a9b-aed7-95f5e677207b)

#### 11. Scorer
The Scorer node is used to assess the performance of your machine learning model. Based on the model's predictions and the actual target values from the testing data, it computes several performance measures including as accuracy, precision, recall, F1-score, and more.

![scorer](https://github.com/nicaaaaaaa/codeless-data-science-fundamental-2023-FTU-x-UMK/assets/93868117/5197a8b6-f83a-422d-8e70-a3e36260b173)

#### 12. Scatter Plot
Scatter Plot nodes are used for data visualisation. They enable you to generate scatter plots to investigate the connections between variables or to visualise the distribution of data points.

![scatter plot](https://github.com/nicaaaaaaa/codeless-data-science-fundamental-2023-FTU-x-UMK/assets/93868117/945790a8-e1f3-4d6e-8102-cfa0dde2887e)

## Results

### Access Data

![result 1](https://github.com/nicaaaaaaa/codeless-data-science-fundamental-2023-FTU-x-UMK/assets/93868117/30425e4f-b754-4914-95d1-95c03b328193)

### Color Manager

![result color](https://github.com/nicaaaaaaa/codeless-data-science-fundamental-2023-FTU-x-UMK/assets/93868117/957a0d30-524d-49de-86fa-165679e7d42d)

### Partitioning

#### First Partition

![1st partition](https://github.com/nicaaaaaaa/codeless-data-science-fundamental-2023-FTU-x-UMK/assets/93868117/b24a3e25-a3e1-46b7-9646-1a4ddc666585)

#### Second Partition

![2nd partition](https://github.com/nicaaaaaaa/codeless-data-science-fundamental-2023-FTU-x-UMK/assets/93868117/33f8d7e8-1eaa-408b-8bdf-d972288ed62a)

### Pie/Donut Chart

![Screenshot (80)](https://github.com/nicaaaaaaa/codeless-data-science-fundamental-2023-FTU-x-UMK/assets/93868117/d01307a8-21d0-4947-87d0-b5793c7c8068)

### Bar Chart 

![Screenshot (81)](https://github.com/nicaaaaaaa/codeless-data-science-fundamental-2023-FTU-x-UMK/assets/93868117/d82d9e60-3661-4350-9a49-2cb1376f31f7)

### Statistics

![statistics 1](https://github.com/nicaaaaaaa/codeless-data-science-fundamental-2023-FTU-x-UMK/assets/93868117/c13db1b4-6736-42e7-a413-683f9d9e9e94)

![statistic 2](https://github.com/nicaaaaaaa/codeless-data-science-fundamental-2023-FTU-x-UMK/assets/93868117/180a2a08-211c-4ef6-8062-8178001bee86)

![statistic 3](https://github.com/nicaaaaaaa/codeless-data-science-fundamental-2023-FTU-x-UMK/assets/93868117/f1c869ad-84ad-4f1b-88a8-049099ca2bf8)

### Scatter Matrix (local)







