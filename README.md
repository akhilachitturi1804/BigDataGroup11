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
### EXAMPLE DESCRIPTIVE QUESTIONS
* What are the most common attributes of our customers, and how do they relate to their buying behavior?
* How do product reviews or ratings affect sales or customer satisfaction, and what are the most common themes or sentiments in the reviews?
* How does employee productivity vary across different teams or departments, and what factors contribute to the differences?
### EXAMPLE PREDICTIVE QUESTIONS
* What are the long-term impacts of our business decisions, and how can we use data to make more informed and sustainable choices?
* What are the long-term impacts of our business decisions, and how can we use data to make more informed and sustainable choices?
* How do our products or services compare to those of our competitors in terms of customer satisfaction, and what can we do to improve?
# Deliverable 2
## Data Understanding
### a) Exploratory Data Analysis:
We uploaded the data to an S3 bucket named it group11project dataset.

<img width="452" alt="image" src="https://user-images.githubusercontent.com/113271948/236286928-ac0cbb3f-f2ba-4df1-b15c-05ed2ba1a2cb.png">
### b) Data preparation 
Fetching the dataset with Jupyter Notebook, we used the following code to read the dataset:


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
## 8. Evaluation and Optimization
AWS provides many machine learning models and tools for analyzing data. However, linear regression is chosen as it is a great method for showing patterns and relationships between sets of data. Linear regression creates a linear equation to model the connection between two variables based on the observed data. One variable is considered as a cause or explanation, while the other variable depends on it.
## 9. Results
The following link provides predicted prices based on specific parameters such as body type and fuel type, after performing pre-processing operations on relevant data and including all necessary parameters. The results of certain inquiries are discussed based on accurate data.
a) Which fuel type vehicles are having higher priority?
The bar graph and pie chart reveal that most vehicles (86%) run on gasoline fuel type, making it the most preferred option. The next popular fuel type is diesel (14%), followed by electric (0%). The visual representations of these graphs can be viewed below.

<img width="343" alt="image" src="https://user-images.githubusercontent.com/113271948/236291198-4b6572c5-eb89-447b-a5e8-01121a64114c.png">

<img width="349" alt="image" src="https://user-images.githubusercontent.com/113271948/236291228-224a468a-7243-4a78-b860-e31d472b0145.png">

b) What color attracts the most customers?

The graph depicts the percentage of customers who prefer different car colors. The most preferred car color is white with 28% of customers choosing it. It is followed by grey with 20%, black with 18%, and silver with 11%. The least preferred colors are green with 4%, brown with 2%, and violet with 1%. Overall, most customers prefer darker shades like grey, black, and silver over lighter shades like white, red, green, and yellow.

<img width="383" alt="image" src="https://user-images.githubusercontent.com/113271948/236291325-5f23bddb-809c-4249-bbb7-ca7d52f582ea.png">


