<h1 id="Portfolio">Portfolio</h1>

- <a href="#BS">Basic Science</a>
- <a href="#ED">Excel Dashboard</a>
- <a href="#SQL">MS SQL</a>
- <a href="#PBI">Power BI</a>
- <a href="#PYT">Python</a>


<h2 id="BS">Initial Project: Basic Science</h2>

<img src="images/AntGroup.jpg?raw=true"/>

<p>
This was the initial project where the objective was to have a better understanding on what is Data Science.
We were tasked to search for practical applications/use cases of data science in the article(s) and identify the different aspects of the basics of data science application to that selected articles.
</p>

<p>
I selected Ant Group as the point of research and gathered few articles on how Ant Group transformed itself to a smart business by using machine learning to leverage data. I learnt that Ant Group utilised big and real time data from Alibaba and Alipay to generate credit scores and analysed and calculate the amount to lend and the interest to charge. This process allowed them to create a scoring and lending system. Their success was largely due to the easy access to big real time data and using these data to their advantage through machine learning and AI technologies.
</p>

<p>
Through this project, I understood that data analytics is important and crucial to company's growth and enabled the company to transform to a smart business which differentiated them from traditional businesses. Company needs good data management and analytical tools to make informed decision as data is only good if we know how to use it.
</p>

[Download PDF](pdf/AntGroup.pdf)

<a href="#Portfolio">Back to top</a>

<h2 id="ED">Capstone Project 1: Excel Dashboard</h2>

<img src="images/Diamonds.jpg?raw=true"/>

<p>
The first Capstone project required us to showcase our dashboard in excel. We were to search for raw data and 'clean' the data through the Power Query application in excel.
The data on diamonds caught my attention and I decided to use this data for the project. Although the data had only 10 columns, it had about 54,000 rows which made it a relatively large dataset.
Thankfully, the data was quite complete and little to be done on 'cleaning' the data.
</p>

<p>
The objective of the analysis was to create visualisation of the data and to estimate the price of diamonds given some features.
In the midst of preparing the visuals on carat size, the different carats in the raw data made the chart difficult to read. Therefore, I grouped the carat sizes into few categories and the grouping made the chart more presentable.
For the visualisation, I focused on the 4Cs: Carat, Color, Clarity and Cut.
The dashboard can be seen from below image.
</p>

<img src="images/Diamonds_Dashboard.jpg?raw=true"/>

<p>
The visuals presented meaningful insights to different aspects of the data. Using the pie charts for the proportions of the 4Cs showed the numbers of diamonds in each category, while the hybrid of bar and line charts showed the count and average price of the diamonds in different categories.
Slicers were also added for easy filtering. When the different categories were sliced, the charts changed accordingly. This enabled us to look at the charts based on the selection and gain insights such as trends.
From the chart analysis, I was able to conclude that the dominant factor of diamond's price is the carat size.
</p>

<p>
To add more fun to the project, I created an average price graph for the estimation of diamond price based on selected features. A fellow classmate was to indicate the 4Cs in which an estimated price from the graph was given based on the selection.
The graph can be referenced from the image below.
</p>

<img src="images/Diamonds_Price.jpg?raw=true"/>

[Download PDF](pdf/diamonds.pdf)

<a href="#Portfolio">Back to top</a>

<h2 id="SQL">Capstone Project 2: MS SQL</h2>

<img src="images/HairSalon_Main_SQL.jpg?raw=true"/>

<p>
In Capstone Project 2, we were to ulitise the SQL commands and functions to perform queries on a dataset, analysis on the queries, load the queries into excel and create interactive Dashboard and visualisation using excel dashboards.
For this project, I used a dataset of a Hair Salon.
</p>

<p>
The most challenging part of this project was to create a new list of customers with details such as first and last name and contact numbers, which was totally unrelated to the SQL course. The customer list was essential to make the queries and analysis more relevant. Thus, I challenged myself to create such a list.
The data on the customers had only client ID and gender. The client ID from Booking and Cancellation tables were used as the unique key and the gender was defined from the services rendered in the Booking and Cancellation tables. In order to make the list more realistic, I used the common first names by genders and common last names in US and randomised the names based on the gender of the client in the table. Contact numbers were also randomised using a formula that I found through the web.
</p>

<p>
The importance and success of this project were to extract the relevat data from the tables in SQL using the specific or appropriate SQL syntax. This was not an easy feat as it required logical thinking and understanding of the syntax. There were a few instances where the mighty Google was needed to search for the suitable syntax.
Below are few examples of the SQL syntax used to the extract the information and charts created to visualise the analysis.
</p>

<img src="images/HairSalon_Busiest.jpg?raw=true"/>

<img src="images/HairSalon_Topclients.jpg?raw=true"/>

<img src="images/HairSalon_NoShow.jpg?raw=true"/>

<img src="images/HairSalon_StoredProcedures.jpg?raw=true"/>

<img src="images/HairSalon_Functions.jpg?raw=true"/>

[Download PDF](pdf/HairSalon_PP.pdf)

<a href="#Portfolio">Back to top</a>

<h2 id="PBI">Capstone Project 3: Power BI</h2>

<p>
The main aim of this capstone project is to exhibit the stages of the data lifecycle using PowerBI on the dataset. It was required to create reports and interactive dashboard in PowerBI.
</p>

<p>
The data on UK car accidents was chosen for this project. The data contained multiple columns and details which were suitable to display the attributes learnt in PowerBI module. Minor amendments were done such as removed unwanted rows and columns, replacing values and adding conditional column. To differentiate the timings of the accidents as day or night, a formula was applied to create a column for the purpose.
</p>

<img src="images/UKAccidents_Questions.jpg?raw=true"/>

<p>
Questions were set for the analysis and visualisations.
</p>

<img src="images/UKAccidents_PowerBI.jpg?raw=true"/>

<p>
The dashboard contained visuals and chart pertaining to the questions. It was found that most of the accidents happened in the Day time, during the morning and evening rush hours. The highest percentage of accidents occured at about 50km/hr with the large number of accidents involving 2 cars. On the whole, lighting and road conditions had little influence on the accidents. It was no doubt that most of the accidents happened in the cities where population were dense.
</p>

[Download PDF](pdf/UK_Accident.pdf)

<a href="#Portfolio">Back to top</a>

<h2 id="PYT">Capstone Project 4: Python (Modelling)</h2>

<p>
Python was the hardest module of the course and the project timeline was short given that the codes were not easily understandable. As such, multiple trials and errors on the coding were explored for this project.
We were tasked to formulate the hypothesis/objective, perform feature engineering, build the machine learning models and evaluate the performance of the models.
</p>

<p>
The dataset, Diamonds, of capstone 1 project was chosen for this instance in view of the familiarity with the data and limited time for data search. The objective was set to predict the diamond price within 15% difference and predict the price of a diamond with given features.
3 models, Simple Linear Regression ("SLR"), Multiple Linear Regression ("MLR") and Random Forest Regression ("RFR") were used for the prediction of the price. Similarly, I focused on the 4Cs as the main features of the models. As SLR model required only 2 variables, Carat (X) and price (Y) were selected. For the rest of the models, 4Cs (X) and price (Y) were selected since the models catered for multiple features and these were the suitable features.
</p>

<p>
Mean Absolute Error was used to evaluate the models as I am looking for the absolute difference and the comparisons of predicted versus observed.
The RFR model had the least mean absolute error, best training and test score and the percentage of the price difference below 15% was the highest. This meant that the RFR model had the highest prediction accuracy. The predicted price was derived by selecting specific features. The predicted price was close to the prices quoted by few websites of diamond sellers, which also validated the accuracy of the RFR model prediction.
</p>

<p>
Feature importance in determining the diamond price was also charted. Unsurprisingly, carat is the most important feature. However, even though carat is the most important feature of the diamond price, we cannot solely based on carat to predict the diamond price (as evident in SLR model). 
</p>

<img src="images/Diamonds_Python.jpg?raw=true"/>

<img src="images/Diamonds_Python_Results.jpg?raw=true"/>

<img src="images/Diamonds_Python_Feature.jpg?raw=true"/>

[Download PDF](pdf/Diamonds_df.pdf)

<a href="#Portfolio">Back to top</a>






---

