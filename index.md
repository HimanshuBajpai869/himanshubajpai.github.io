## Professional Experience

#### Tiger Analytics | Lead Engineer - Machine Learning Platform | October-2022-Present

=>  Leading the effort to build the No-Code Machine Learning Platform for Data Engineers and Data Scientists.

=> Development of MLOps Framework for Real Estate Client : Build capabilities to operationalize and manage the solutions developed by Data Science Team.

Tools/Technologies Used: Python, MLFlow, Mathematical Modelling, DevOps, PowerApps, API.

- Revamped the existing mathematical modelling solution based on Convex Optimizer to consume Gurobi solver with no impact on execution time.
- POC on CI-CD pipeline to move the code to different databricks environment.
- POC on leveraging ML-Flow to track the execution of workflow with relevant KPIs.
- Developed a databricks job to import the event data from Google Big-Query to Databricks Delta lake with improved runtime from 11 days to 2.5 days.
- Developed a Power-App to help users to pass model parameters to perform custom execution of notebooks via databricks Jobs API.


#### Fractal Analytics | Machine Learning Engineer | October-2021-September-2022
Working on bringing Machine Learning system to production to help business stakeholders make decision based on analytics.

=> Automate OnPrem DS Solution : To migrate the on-prem Data Analytics solution to Microsoft Azure. Provide a UI so that Data scientists .can run their experiments based on input parameters and visualize the results in Power-BI and allow them to publish the results for business user to understand the story.

Tools/Technologies Used: PySpark, ETL, Python, SQL, GitHub, Scala, Databricks, Storage Account, REST API, Microsoft Power Platform (PowerApps, PowerBI)

1. Designed the pipeline to maintain the state management across all the tasks while running an experiment
2. Wrote Databricks job to transform raw data to data in the standard format.
3. Wrote Databricks job to perform aggregation on the data in a standard format to make it ready for running experiment.
4. Worked on optimizing the time and resource consumption and was able to reduce the time from 9 hours to 1 hour on a low-end cluster.
5. Developed a UI on PowerApps, with SharePoint List-based authentication, to run the experiment (Databricks Job).
6. Worked on establishing the connection to read data from the storage account or upload it to the storage account.
7. Worked on Power BI report to visualize the results and added support to update the back-end data from PBI using PowerApps.

=> Secure Data Science Solution : Building a scalable system that secures the data science solution and provides a utility to the Client to consume it in Pay-As-You-Go-based licensing mechanism.

Tools/Technologies Used: Python, Azure DevOps-CI/CD, Flask, Azure Application Service, Application Insights, Logic App, Storage Account, Azure ML, YAML.

- Designed a MicroService-based architecture to allow the users to consume the data science solution as a black box but with the feasibility of training model with different combinations of parameters. Hence, maintaining the security of the data science solution and client data.
- Designed an architecture to obscure the solution with the license and support a Flask API to retrieve the secured URL valid for a particular time duration.
- Developed a Flask API with OAuth to validate the request and send the secured URL (Shared Access Signature) of the package.
- Designed a basic Database schema to facilitate the obscurification of package for a client with the proper license mechanism.
- Created CI/CD pipelines to continuously build and deploy the API to App Service.
- Created a Build Pipeline to obscure the package with the license on the fly and push it to the blob storage.
- Created CI/CD pipeline to push the encrypted package on client to different environments like Development/Test/Production etc.
- Created different alerts for monitoring the service-
 a. Notify client when license is about to expire in a month
 b. Auto-Shut Down App Service when not in use.
 c. Alerts to notify the failure while running ML Pipeline or deploying Model.
 d. Alert team in case any runtime exceptions are logged under Application Insights.

Benefits:
1. Maintain Data and Solution security on both client and developer sides.
2. Provide a mechanism for Pay-As-You-Go model. The solution stops working the moment license is expired.
3. Automation with CI/CD pipeline helped in reducing manual effort significantly.

- [KudoBoard shared by the team](https://www.kudoboard.com/boards/TDKsx6Ri)

<img src="images/kudoboard_sdss.png?raw=true"/>

=> Marketing Mix Modelling for Sponsorship Return of Investment : Improve the existing solution of the client to understand the impact of different marketing channels on sales and estimate Sponsorship ROI from each channel using Marketing Mix Modelling.

Tools/Technologies Used: Python, Marketing Mix Modelling, Hierarchical Modelling, Time Series Analysis.

- Re-designed the code with OOPs, logs and exception handling for better understanding and maintenance of the code.
- Tried out multiple approaches to perform improved Marketing Mix Modelling-PyMC3, PyStan, Robyn and improvements on adstock transformation using Weibull.
- Wrote multi-threading job to process the raw data with lesser time.
- Added support to run multiple iterations of the model using Nevergrad Multi-Objective function with semi-automation leading to improvement on execution time from 1 iteration with 1100 seconds to 10 iterations in 850 seconds.

#### Infosys Limited | Technology Analyst | August-2018-September-2021
Part of the Microsoft Management Services Team where I focussed on:
1. Developing Micro services managing cloud resources using ARM Azure SDKs powershell and CSharp.
2. Creating load tests which run 24x7 to identify the bugs before deploying the code to production.
3. Preparing the performance dashboards to show the real-time test results and the details of resources in the cloud.
4. Worked on optimizing the cost and reliability of the service using different code practices and Azure services.
5. Developed a Data Science Solution for better management of live site incidents which was not only capable of triaging the incidents but also recommends possible solution.
6. Created a chat-bot based on Azure AI to onboard new team members by helping them with Knowledge Transfer and assist them in DRI activities.

Tools/Technologies Used:
• Language: C#
• SQL: Azure SQL, and Cosmos DB.
• Azure Services: Service Fabric, Virtual Machines, Storage Accounts/DataLake, Virtual Network, Network Security Groups, SQL DB, Cosmos DB, Key Vaults, Automation Account, Application Gateway, Load Balancers, AAD, Data Factory.
• Azure Resource Management: Azure Resource Management (ARM) templates, SDKs, and PowerShell.
• Software Development Technique: Micro Services.

Other Responsiblities - Participated in Recruitment Drives and RFP work to develop POCs for value-add services.

#### Infosys Limited | Senior System Engineer | May-2017-July-2018
Joined Microsoft Account where I was part of:
1. Data Services team where focus was on maintaining automated test cases and bug fixing.
2. Solutions Team where focus was on fixing bugs related to solution import and export. Worked extensively in adding telemetry for the same. Saved time of time by working on classifying the errors into User or Platform Errors.

#### Infosys Limited | System Engineer | June-2015-April-2017
Part of Education Training and Assessment Unit where I played different roles - Batch Owner, Educator, Mentor, Content Creator and development and maintenance of applications used for managing the curriculum for the trainees.

---

## Accolades
- [Won the Coronavirus Analysis challenge in the first ever UNICC Data for Good Hackathon as a team](https://www.unicc.org/news/2021/03/12/abraca-data-a-team-of-young-talent-forged-by-chance-fortified-by-data/)
- [Pinnacle Award | ENG Achiever | December-2020]()
For being outstanding performer in the unit for the cycle September-2019 to October-2020.
- [Best Skilling Performance | July-2020]()
For being continuous learner with primary focus on Data Science.
- [Glory Awards | Kudos Award | February-2020]()
For outstanding support and winning client appreciation for the work done in the project in FY2020-Quarter-3.
- [Insta Award | November-2019]()
For coming up with the idea of implementing CI and CD pipeline to save production outages for the client.
- [Insta Award | September-2019]()
One of the top performers in the Microsoft Account and skilling in Data Science and for being mentor to new members.

---

## Certifications
#### Microsoft Certifications
- [Azure Data Scientist Associate](https://www.youracclaim.com/badges/dfbfcbd8-02b7-467b-95f1-1d4a9bd88285)
- [Programming using C#](https://www.youracclaim.com/badges/06c1cb4b-db80-4cee-b6e4-7464fbd890ed/linked_in_profile)
- [Azure Fundamentals](https://www.youracclaim.com/badges/68e295a5-dd80-40c0-b0b2-eb769f13611d/linked_in_profile)
- [Azure Developer Associate](https://www.youracclaim.com/badges/b775c6dc-2981-4928-bd7b-0f964a73b65f/linked_in_profile)
- [Introduction to Programming using Python](https://www.youracclaim.com/badges/1b090fc3-cbbc-4bb7-9b87-638b3ac99ab7/linked_in_profile)

#### Data Science Certifications
- [IBM Data Science Specialization](https://www.coursera.org/account/accomplishments/specialization/PGLG7NYV26VR)
- [Coursera Applied Text Mining in Python](https://www.coursera.org/account/accomplishments/verify/9TGY58ZEBW4Z)
- [DataCamp Machine Learning Scientist with Python](https://www.datacamp.com/statement-of-accomplishment/track/d532e92e83c250bd735bd757a95a5026f151d76f)
- [DataCamp Deep Learning with Python](https://www.datacamp.com/statement-of-accomplishment/track/0ff172970091cacc2ee5ca0dda0b512e48864854)
- [Udacity Data Scientist Nano Degree](https://github.com/HimanshuBajpai869/Udacity-DataScientist)
- [Udacity Natural Language Processing Nano Degree](https://confirm.udacity.com/E99KPKF)

---

#### Experience with Microsoft Services
<img src="images/Skills.png?raw=true"/>

---

#### Experience with Data Science Libraries
<img src="images/pythonlibraries.png?raw=true"/>

---

## Education

#### Master of Technology in Software Systems with Specialization in Data Analytics
##### Birla Institute of Technology and Science, Pilani, India - 2018-2020 - CGPA - 7.4
[Post Graduate Thesis - Building ML Based intelligent system to analyse Production Live Site Incidents](https://www.ijeat.org/wp-content/uploads/papers/v10i3/C21780210321.pdf)
1. Studied the incidents and prepared the set of rules required to pre-process the text data before applying the Machine Learning Model
2. Studied the performance of different Classification models on the processed data set using Cross Validations and different performance metrics to identify the best go-to solution for classifying the incident.
3. Studied different text similarity models to identify the similar incidents which may be recommended as the solution for the incident.
4. Combined the obtained best go-to classification model and recommender system model into a Flask based API which can be used by end user to triage and get the recommended solution for the ticket.
5. The technical paper is published in February edition of International Journal of Engineering and Advanced Technology journal.

#### Bachelor of Technology in Mechanical Engineering
##### Dr. APJ Abdul Kalam Technical Univesity, Lucknow, India - 2011-2015 - Percentage - 80
[Under Graduate Thesis - Wind Turbine Speed Modulation](https://www.slideshare.net/secret/dWgkGicqsUFQSY)
1. Developed a working model using CVTs which helps in maintaining the RPM of the turbine in the cases where the wind speed falls below the threshold.
2. Studied the improvement observed after using this model and the possible improvement areas.

---

## Personal Projects

- [Real or Not? NLP with disaster tweets](https://bajpaihimanshu.medium.com/real-or-not-nlp-with-disaster-tweets-77ab3ba8325f)
- [Auto Evaluate Answers](https://github.com/HimanshuBajpai869/AutoEvaluateAnswers)
- [Co-WinTogether](https://github.com/HimanshuBajpai869/CoWinTogether)
- [UNICC-Hackathon-ImpactofCovidOnChildren](https://github.com/HimanshuBajpai869/UNICCHackathon-CovidAnalysis/blob/master/ImpactofCovidOnChildren.ipynb)
- [Miscellanious Projects](https://github.com/HimanshuBajpai869/DataScienceProjects)

---