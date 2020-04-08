# CFPB-Analysis
---
## Self introduction  
This team is made up of six people: [Yihui Yang(MSBA)](https://www.linkedin.com/in/yihui-sam-yang-771aa5147/),
[Jiarun Li(MSBA)](https://www.linkedin.com/in/jiarun-li-98779a135/),
[Shuang Wu(MBA)](https://www.linkedin.com/in/shuang-w/),
[Xiuqi Wang(MSBA)](https://www.linkedin.com/in/xiuqi-wang-296241172/),
[Baiting Gai(MSBA)](https://www.linkedin.com/in/baiting-claire-gai-81413b159/),
[Ziyi Zhang(MSBA)](https://www.linkedin.com/in/ziyi~zhang/).
We are students from [The Lally School of Management](https://lallyschool.rpi.edu/) at [Rensselaer Polytechnic Institute](https://www.rpi.edu/).  
## What is Datathon  
Just like Hackathon, datathon aims to test students' ability to find and solve problems based on the given data and task in a limited time. The time limitation here is **24** hours. All groups have **15** minutes to present their works to the judges who are senior Ph.D. students or professionals in their industries, especially in data analysis.   
## Data source  
[CFPB Data](https://catalog.data.gov/dataset/consumer-complaint-database#topic=consumer_navigation)  
## Problem Statement  
> Using the above data source and any others from your own research, create analytics and make conclusions so that you can advise cfpb on its future plans, actions, and legislation proposals so that this market becomes more efficient and the number of consumer complaints decreases.  

> Specifically, identify the products, sub-products, issues and sub issues as well as corporations and sub sectors that create most problems for the consumers.  Search through the consumer text narratives to identify the top areas of consumer complaints.   

> Identify all possible factors, existing in this dataset or not, that have the highest impact in leading to consumer complaints.  Provide advice to the federal government and propose five specific pieces of legislation to the US Congress.  

## Deliverables  
1. [Tableau](https://github.com/samileyang/CFPB-Analysis/tree/master/Tableau)  
2. Code in [R for data cleaning]()  and [Python for ngram&wordcloud]()   
3. [Slides](https://github.com/samileyang/CFPB-Analysis/tree/master/Slides)  

## Conclusion  
1. Enhance monitoring on new-categorized and emerging products/services  
    * Requirements for supporting procedure/system updates when updating product catalog  
2. Regulations to decrease untimely response rate  
    * Set upper limit  
    * Information transparency --blacklist of companies with high untimely-response rate  
3. Legislation on complaint handling  
    * Complaint Close Procedure
4. Consumers education and training  
5. Regulations to improve small companies’ effectiveness  
    * Industry Seminar/ coaching 
    * Required training for complaint handling personnel 
6. Legislation on preventing identity theft  

## Exploratory data analysis   
1. business model for CFPB   
![Business model for CFPB](https://github.com/samileyang/CFPB-Analysis/blob/master/pics/business%20model.png)  
Consumers can submit their complaints on [CFPB official website](https://www.consumerfinance.gov/). It will take CFPB a while to handle this issue. Then, CFPB sends the issue to the financial companies. After these companies receive the complaints, they should provide resolution and response to the customers.  
2. distribution of annual complaints  
![distribution of annual complaints](https://github.com/samileyang/CFPB-Analysis/blob/master/pics/distribution%20of%20annual%20compaints.png)  
3. Products in each year
![Products in each year](https://github.com/samileyang/CFPB-Analysis/blob/master/pics/Products%20in%20each%20years.png)  
4. Number of complaints per 100k people over time  
![Num of complaints per 100k people over time](https://github.com/samileyang/CFPB-Analysis/blob/master/pics/Num%20of%20complaints%20per%20100k%20people%20over%20time.png)  
5. Products & sub products  
![Products & sub products](https://github.com/samileyang/CFPB-Analysis/blob/master/pics/Products%20%26%20sub%20products.png)  

## How we thought about this question
First things first, before we actually move on, we need to define what the market efficiency means in this circumstance. 
Based on the report from CFPB and our understanding, we provide this graph.  
![business model](https://github.com/samileyang/CFPB-Analysis/blob/master/pics/Our%20definition%20of%20market%20efficiency%20for%20CFPB.png)  
Decreasing the total time spending on the complaints is our [*North Star Metric*](https://growthhackers.com/articles/north-star-metric) . Undoubtedly, there are three aspects we should focus on:  
1. CFPB Internal Efficency  
2. Company Efficiency  
3. Consumer Efficiency  


