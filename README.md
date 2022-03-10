# HR_Attrition_Prediction_Semicolons2022
A Project on HR Attrition Prediction

### Architecture of the Project

![image](https://user-images.githubusercontent.com/47893951/157627362-bcd4fd2a-2ce6-4c36-9345-98c7426ba733.png)


![image](https://user-images.githubusercontent.com/47893951/157629012-649a9d93-7daa-473b-b5eb-455876c77265.png)


As part of out project, Firstly, we have performed the Exploratory Data Analysis using Python.
You can find the links to the notebook here: 

[EDA-Colab-Notebook](https://colab.research.google.com/drive/1G19UdzxxaqsxqX4pdgYPqCdgYaWpeY4U?usp=sharing)

[Notebook-Github-Link](https://github.com/yogi2022/HR_Attrition_Prediction_Semicolons2022/blob/main/HR_Attrition_Prediction_Semicolons2022_notebook1.ipynb)

Here, we have analysed the data and made some visualizations that would help us.

You could find some visualization here:

![image](https://user-images.githubusercontent.com/47893951/157628798-20188012-403d-4932-b91d-ec8b3b62d47a.png)




![image](https://user-images.githubusercontent.com/47893951/157628704-8ce18c51-e5bb-4017-9f7a-4fcc48309b68.png)



Later, we built a model on IBM Watson by using AutoAI service.

The technologies we used are:

![image](https://user-images.githubusercontent.com/47893951/157628930-d6ee2740-0a1d-4f3c-a629-4af994146c0e.png)


Workflow:

After performing Exploratory Data Analysis, and Data Cleaning part, We used IBM AutoAI Service to build and deploy my model.

![image](https://user-images.githubusercontent.com/47893951/157630441-deb8437f-e7ef-4ca7-b5d3-184320b297a9.png)


Here are some screenshots of the model that is deployed

We have used 90% of the data to train and 10% for test

![image](https://user-images.githubusercontent.com/47893951/157631628-3c71b113-91c1-4c20-9a12-b441028495f9.png)



![image](https://user-images.githubusercontent.com/47893951/157631663-c6de18c7-c6fd-49cb-990f-b103d107fc2d.png)



![image](https://user-images.githubusercontent.com/47893951/157631730-7704fd3d-5da5-4732-92a6-14c29a8351ee.png)



![image](https://user-images.githubusercontent.com/47893951/157631754-fad09a9b-35e7-40e6-812a-fcc18b3cc281.png)




Algorithm Sugession:

![image](https://user-images.githubusercontent.com/47893951/157631865-4b6efa4d-bcb5-4cfb-8f4b-a926606dba6b.png)
 


So, we used the algorithm called, Random Forest Classifier 


Later we did the testing part. We can give the input manually with the help of the form, and also we can give the input by using json format.


![image](https://user-images.githubusercontent.com/47893951/157633269-df00738e-b536-4c62-b8eb-dee407b200a7.png)


The Result can be obtained in this below format.

![image](https://user-images.githubusercontent.com/47893951/157633796-144a2ed2-5182-4201-b11e-50eda91786ea.png)


## Future Updations


#### Integration Part

We also thought of integrating our Model that is present on IBM cloud pak to our web application.
So, we need to provide authorization and API Autherization is required, as we are using Machine Learning service from IBM cloud pak. So, we need to integrate that service by providing service creditials to our python flask code.

So, we made a basic UI form. Later, we would be integrating our Model to our Web App.



![ezgif1](https://user-images.githubusercontent.com/47893951/157637050-60150459-1849-4744-b26a-9cd37891b06a.gif)




#### Dashboards

Also, we thought of making attractive, dynamic and responsive dashboards and integrating them to our web app. We coudl use Tableau, PowerBI, MS Excel and other BI tools, Visualization tools to make those dashboards.


#### Automation using Power Query in MS Excel

We also thought of doing an automation kind of thing, where we will prepare a report for our existing data, and whenever we get the new data, when we upload that dataset to the folder where we made a report of the similar format, by just refreshing, we could obtatin the instant results and report for our new data of same format which is uploaded as a new data in that folder.


#### Chatbot Integration

We can also integrate a chatbot to our web application


#### Website/Dashboard Visualization Assistance

We can also make out web application smart by adding smart assistance into it, like the voice assistant, and chatbox so that, we can type or just speak the results that we want to get and it will show you the visualization instantly. eg: Show me the employees whose age>35 and work_experience>5.


#### Email writing service

When the HR Managers, Project Managers come to know regarding the information about an employee who is probably want to leave the company, so they could think of some external factors that is generated as a report in our web application and they could use those results and they can be in touch with that employee who is thinknig of leaving the company, and they can provide some benifits according to the results that repot has generated in our web application. 

So, these are some of the future updations that we could think of.



