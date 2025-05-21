This is a job simulation in which we will be using Excel, Tableau for data cleaning, data analyzing, data modeling and creating data insights to answer business related questions
Iam participated in Deloitte's job simulation on the Forage platform, and it was incredibly useful to understand what it might be like to be part of the team at Deloitte.
I was able to analyse data and create a dashboard. I practised using Tableau and Excel and built my data analysis skills in a real-world context.
Doing this program confirmed that I really enjoy working on technology problems for clients and I'm excited to apply these skills on a team at a company like Deloitte.

Introduction:

Task 1: Data analysis
Here is the background information on your task
Using a data unification algorithm, the tech team at our client, Daikibo, has converted all telemetry data collected from its 4 factories:
Daikibo Factory Meiyo (Tokyo, Japan)
Daikibo Factory Seiko (Osaka, Japan)
Daikibo Berlin (Berlin, Germany)
Daikibo Shenzhen (Shenzhen, China)
Each location has 9 types of machines, sending a message every 10 mins. Daikibo has been collecting this data for one month (May 2021) and they've shared this data in the form of a single JSON file.
The reason the client wanted to collect telemetry was to answer 2 questions:
In which location did machines break the most?
What are the machines that broke most often in that location?
Install Tableau on your computer and register an account with the same email you used to download the software.
Download the daikibo-telemetry-data.json.zip file -> unzip -> and import it in Tableau.
Create a calculated measure field called "Unhealthy" with a value of 10 for every unhealthy status (representing 10 mins of potential down time since the previous message).
Create a bar chart called “Down Time per Factory”.
Create a new sheet with a new bar chart called “Down Time per Device Type”.
Create a Dashboard with the 2 previous sheets and set the first chart to be used as a filter (selecting a factory in the first chart shows only the down time of the machines in this factory in the second chart).
Select the factory with the most down time (click on its bar), make a screenshot of the dashboard and upload it as a submission for this task.

Task 2: Forensic technology
Here is the background information on your task
After a worrisome number of internal complaints about gender inequality in terms of salary, Daikibo Industrials wants us to help them investigate.
The Forensic Tech team has built an algorithm to quantify “level of gender pay equality” for most job roles within the company, in all company locations. Our Forensics lead thinks it would be a great idea for you to finish the job.
Create a 4th column (Equality class), classifying the equality score into 3 types:
Fair (+-10)
Unfair (<-10 AND >10)
Highly Discriminative (<-20 AND >20)
Examples:
10 → Fair
-9 → Unfair
-30 → Highly Discriminative
Please find the Equality Table you need to edit in the resources below. When you are done, upload the edited version of the file.
