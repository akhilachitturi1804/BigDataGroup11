# BigDataGroup11
# Deliverable 1
## 1. TEAM
### a) Members
* Nihar Gopidi 
* Akhila Chitturi
* Akhil Vadlakonda
* Dinesh Reddy Kankanala
* Shashank Patlolla
### b) Communication plan to include project artifact repository, meeting notes, meeting platform, etc.
* Communication Methods: Google chat group is created for day-to-day conversation and syncing. Email for a more formal and documented way of communication.
* Response times for communication: The team members communicate with each other and response time of each member is as minimum as possible. If any team member is absent or away from work place it is informed in the group communication network.
* Attendance in Meeting: We have made few fixed timings which is comfortable for everyone and made it mandatory for everyone to attend, but if informed earlier exemption can be granted. we also have made few optional meetings this means that it is not mandatory for all team members to attend every meeting but at least 3 out of 5 members need to be present. The ones not attending shall inform the rest well in advance. It is appreciated if all can attend anyways.
* Publish control: All changes made by the team members are pushed to the artifact by raising pull requests which are reviewed by the peers before merging.
* Team work and work Division: Work is divided between the team members in the form modules. If anyone faces an issue in the work it will be discussed and come to a deterministic understanding. Any overload can be brought to the notice of the other members so it can be divided or redistributed.
## 2. Selection of data from the Open Data Registry for Amazon Web Services https://registry.opendata.aws/
### PROJECT ARTIFACT REPOSITORY
All our work can be found in the public repository that has been created on GitHub.
The link to the repository is -
https://github.com/akhilachitturi1804/BigDataGroup11
** ** Car Sales 
### DATASET
(https://www.kaggle.com/datasets/ekibee/car-sales-information)
## 3. Business Problem or Opportunity, Domain Knowledge
The dataset we've selected is from Kaggle, where it was gathered from a well-known website with adverts for vehicles for sale. The dataset is updated weekly and contains information about cars in over 18 columns, including columns for the car's price, brand, fuel type, color, mileage, and power. We can determine some helpful information from this data, such as what price range users are most interested in purchasing in, what type of color appeals to people the most, regardless of cost, what fuel type is valued most, and how to use a correlation graph to understand the correlation between various variables that are closely related. This information reveals which variables in the dataset are closely related so that they can be given more weight.
## 4)  Research Objectives and Question(s)
### RESEARCH OBJECTIVE
Finding the variables that affect automobile sales in the US may be the study goal for analyzing the Car Sales Information dataset from Kaggle. Understanding which automotive features—such as make, model, year, price, mileage, fuel type, etc.—have the most effects on sales volume and price as well as how external factors like location and dealer ratings affect sales—could be the specific objective.
a) Which fuel type vehicles are having higher priority?
b) What color attracts the most customers?
c) Which brands has gasoline as fuel type after 2015?
d) what is the power range that customers are looking for?
e) what is the price range that customers are looking for?

# Deliverable 2
## Data Understanding
### a) Exploratory Data Analysis:

The file for conducting Exploratory Data Analysis has been uploaded to AWS Sagemaker, and the link to access the file is provided here.

https://github.com/akhilachitturi1804/BigDataGroup11/blob/main/Deliverable2.ipynb

We uploaded the data to an S3 bucket named it group11project dataset.

<img width="452" alt="image" src="https://user-images.githubusercontent.com/113271948/236286928-ac0cbb3f-f2ba-4df1-b15c-05ed2ba1a2cb.png">

### b) Dashboard

Fetching the dataset with Jupyter Notebook, we used the following code to read the dataset:

https://github.com/akhilachitturi1804/BigDataGroup11/blob/main/Deliverable_2.pdf

<img width="452" alt="image" src="https://user-images.githubusercontent.com/113271948/236287242-07fb7bdb-91d3-4af9-88b3-1bcfff61ee07.png">

<img width="452" alt="image" src="https://user-images.githubusercontent.com/113271948/236287293-e08e1476-1f4c-4f4f-8b1e-5f9e8e7c1665.png">

<img width="452" alt="image" src="https://user-images.githubusercontent.com/113271948/236287324-ea35f247-3b21-43e0-8fdc-36c79c60a1ad.png">

## Data preparation:
Quick Sight:
This is a pie chart representation between the car colour and the Fuel used the cars. This classifies and helps us to understand what type of fuel cars and what colour of cars were sold in that respective domain.


This is a distribution of the mileage of the cars and the sum of total distance travelled by the car.
<img width="452" alt="image" src="https://user-images.githubusercontent.com/113271948/236287669-2562a411-536e-4068-b4e5-23a142e44ccd.png">

<img width="452" alt="image" src="https://user-images.githubusercontent.com/113271948/236287700-a5ab3f14-4131-4f26-af67-37e580646b3c.png">

<img width="452" alt="image" src="https://user-images.githubusercontent.com/113271948/236287733-8f2dd9df-9401-4341-bab9-0222f50a1d04.png">

<img width="452" alt="image" src="https://user-images.githubusercontent.com/113271948/236287767-ff051849-4721-4505-a97f-7818bc0a29c0.png">

<img width="452" alt="image" src="https://user-images.githubusercontent.com/113271948/236287803-7637aa20-6eec-469f-82e7-e322a9171d7a.png">

<img width="451" alt="image" src="https://user-images.githubusercontent.com/113271948/236287860-3aba1b59-4208-478f-8575-467a8b0bd7e0.png">

<img width="452" alt="image" src="https://user-images.githubusercontent.com/113271948/236287897-71f32637-e22f-4a03-b912-936f3b3894d2.png">

<img width="452" alt="image" src="https://user-images.githubusercontent.com/113271948/236287932-2fa790b7-450a-49e0-9fdb-5b1725361439.png">

# DELIVERABLE 3
## 7. Analytics, Machine Learning
Amazon's machine learning technologies, such as SageMaker, are utilized for analyzing and implementing machine learning. Prior to being processed by SageMaker, the data is first identified using Amazon Athena and Glue. To achieve optimal results using the best machine learning tools for the dataset's structure, the dataset schema is carefully inspected. Finally, Amazon SageMaker is employed to obtain accurate outcomes. In summary, the process involves using Amazon Athena and Glue for data identification, analyzing the dataset schema to determine the best machine learning tools, and applying SageMaker for obtaining precise results.

<img width="451" alt="image" src="https://user-images.githubusercontent.com/113271948/236320948-5b952ef7-0bda-4d80-9821-62b765e26396.png">

<img width="444" alt="image" src="https://user-images.githubusercontent.com/113271948/236320990-a17c929d-70f4-4a6e-beeb-212ef9117673.png">

<img width="468" alt="image" src="https://user-images.githubusercontent.com/113271948/236321013-37f32f38-283c-44b8-b1b0-bc8c25b02c62.png">

<img width="468" alt="image" src="https://user-images.githubusercontent.com/113271948/236321037-60bdf40f-352b-43c7-a01d-b75ec4c35aff.png">




## 8. Evaluation and Optimization

AWS provides many machine learning models and tools for analyzing data. However, linear regression is chosen as it is a great method for showing patterns and relationships between sets of data. Linear regression creates a linear equation to model the connection between two variables based on the observed data. One variable is considered as a cause or explanation, while the other variable depends on it.
## 9. Results
The following link provides predicted prices based on specific parameters such as body type and fuel type, after performing pre-processing operations on relevant data and including all necessary parameters. The results of certain inquiries are discussed based on accurate data.
https://github.com/akhilachitturi1804/BigDataGroup11/blob/main/Deliverable3.ipynb

### a) Which fuel type vehicles are having higher priority?
The bar graph and pie chart reveal that most vehicles (86%) run on gasoline fuel type, making it the most preferred option. The next popular fuel type is diesel (14%), followed by electric (0%). The visual representations of these graphs can be viewed below.

<img width="343" alt="image" src="https://user-images.githubusercontent.com/113271948/236291198-4b6572c5-eb89-447b-a5e8-01121a64114c.png">

<img width="349" alt="image" src="https://user-images.githubusercontent.com/113271948/236291228-224a468a-7243-4a78-b860-e31d472b0145.png">

### b) What color attracts the most customers?

The graph depicts the percentage of customers who prefer different car colors. The most preferred car color is white with 28% of customers choosing it. It is followed by grey with 20%, black with 18%, and silver with 11%. The least preferred colors are green with 4%, brown with 2%, and violet with 1%. Overall, most customers prefer darker shades like grey, black, and silver over lighter shades like white, red, green, and yellow.

<img width="383" alt="image" src="https://user-images.githubusercontent.com/113271948/236291325-5f23bddb-809c-4249-bbb7-ca7d52f582ea.png">

### c) Which brands has gasoline as fuel type after 2015?
The bar graph represents the number of car brands that had gasoline as their fuel type after the year 2015. Each brand is represented by a horizontal bar, with the length of the bar indicating the number of cars with gasoline as their fuel type. The graph shows that there are several car brands with gasoline as their fuel type after 2015. The highest number of cars belongs to Toyota, followed by Lexus, Mitsubishi, and Honda. Other brands such as Subaru, Suzuki, Nissan, and Lada also have a considerable number of cars with gasoline as their fuel type. The graph clearly shows that gasoline is still a popular fuel type among many car brands even after the year 2015.

<img width="388" alt="image" src="https://user-images.githubusercontent.com/113271948/236296226-ca6d0cf6-19b1-43ce-bbd5-cb8de659361d.png">

### d) what is the power range that customers are looking for?

![WhatsApp Image 2023-05-04 at 3 35 17 PM](https://user-images.githubusercontent.com/113271948/236324755-02efac31-4aea-4da0-8511-c97bad93b02e.jpeg)

![WhatsApp Image 2023-05-04 at 3 35 17 PM (1)](https://user-images.githubusercontent.com/113271948/236324860-6ef183a6-3cad-4f51-8124-ae743f03be57.jpeg)

### e) what is the price range that customers are looking for?
The range of prices is the last step of evaluation because it depends on many factors, including brand, body type, color, fuel type, and a number of other features. A list of the final prices is included in the graph along with an estimate of the car's price based on these attributes. The linear regression model is used to determine which prices customers strongly choose. Below, a list of very likely outcomes is provided after all the parameters have been taken into account.
Below is the output for the same.

<img width="468" alt="image" src="https://user-images.githubusercontent.com/113271948/236365463-00e6898b-f600-4d32-8923-c78a96991b17.png">


## 10. Future Work, Comments

### 1. What was unique about the data?  Did you have to deal with imbalance? What data cleaning did you do? Outlier treatment?  Imputation?
The data used in this project was unique and had several features that were useful for predicting customer preferences. However, the data also contained null values which needed to be addressed to improve the performance of machine learning models. The presence of string values in the dataset also created imbalances and had to be transformed into integer values because machine learning models cannot process strings as inputs. To clean the data, the null values were removed from the dataset. The data in each column was carefully analyzed and various statistical distributions such as standard deviation, mean, and maximum were examined to determine how evenly the data was distributed. This information was then used for imputation. Overall, the data cleaning process involved a thorough examination of the dataset to ensure that it was as accurate and complete as possible, which was critical for building a reliable machine learning model.
### 2. Did you create any new additional features / variables?
No new variables were added, but new features were introduced. AWS Athena and AWS Glue were utilized to detect the data in AWS Quicksight dashboards. Linear regression models were used to display the data results during the Analytics/ML modeling stage. AWS SageMaker was utilized to produce the outcomes.
### 3. What was the process you used for evaluation?  What was the best result?
During the project, various AWS resources were utilized, including AWS Glue, AWS Athena, and AWS Quicksight. These platforms were used to identify and understand the data after it had been pre-processed. Once the data was processed, it was transferred to AWS SageMaker, where linear regression was performed to obtain the results. The results were presented in the form of plots using tools such as Matplotlib and other Machine Learning tools. Overall, the goal was to answer the research questions by utilizing the different AWS resources available, ensuring that the data was processed and analyzed in a systematic and efficient manner.
### 4. What were the problems you faced? How did you solve them?
While creating the project, we faced various challenges. One of the major issues was related to the dataset that we selected. The dataset contained null values in its columns, which needed to be pre-processed before proceeding further. As the dataset was from Kaggle, setting it up on AWS services was also a challenge. We also encountered problems while setting up AWS Glue and AWS Athena. Moreover, certain data operations could not be set up initially on AWS services due to credit-related issues.
To solve these problems, we used various strategies. We employed data cleaning techniques such as imputing missing values with zero and transforming string values to integer values to eliminate null values. To address the issues related to the Kaggle dataset, we used AWS Glue and AWS Athena to understand and manipulate the data. Overall, we tackled these challenges by adopting a problem-solving approach and using various resources at our disposal.
### 5. What future work would you like to do? 
The future work includes experimenting with different machine learning models to improve the accuracy of the price predictions. Including more data sources could offer greater insights into customer preferences. Moreover, conducting surveys or collecting additional data from customers could help gain a deeper understanding of their decision-making processes when purchasing cars. Additionally, creating a user-friendly interface to display the analysis results to car dealerships or other stakeholders could be a valuable addition.
### 6. Instructions for individuals that may want to use your work?
The dataset used in this project is sourced from Kaggle, and users who want to reproduce this work will need to set up an AWS environment with the necessary credentials. There may be associated fees for using certain AWS services. Additionally, the user must import the Kaggle data into AWS and configure the AWS SageMaker to execute the Python notebook containing the code. The GitHub repository contains all the necessary details for the procedure, including other requirements.
## Implementation of Work / Presentation Video


