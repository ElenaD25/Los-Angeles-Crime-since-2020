# Los-Angeles-Crime-since-2020

We have the following scenario:

The LA police are facing a significant challenge when it comes to reducing the number of incidents reported from 2020 to the present. To make informed decisions about firing more agents, doing something about the weapons law, strengthening patrols, and any other actions. The police from LA have turned to you to help them identify the reasons why the number of crimes increased like crazy. So, they entrusted you with a comprehensive dataset that contains all the records about the incidents that took place in LA and are waiting for you to come up with some conclusions and help them make important decisions when it comes to reducing those kinds of incidents and protecting the residents.


<h3>🎯 My purpose</h3>

Through this analysis, our goal is to unravel mysteries and address the most pressing questions, ultimately guiding us toward a more effective approach to protecting the residents.

<h3>🕵️‍♀️ Let's begin</h3>

<h4>  Data cleaning </h4>

Receiving the dataset from the police doesn't mean it's already ready for analysis and insight extraction, so I had to perform the most known process - <b>data cleaning</b>.

**Through it, I solved things such as:**
- searched for duplicated values (did not find any)
- replaced NULL values with something more appropriate, such as: "Unknown", "Not specified" etc.
- deleted useless columns
- replaced single character values with the full version of it (eq: F-female, B-black for race, and many more)
- change the column data type (Reported Date, Occured Date from string to datetime data type)
- rename columns for readability


<h4>  Exploratory Data Analysis (EDA) </h4>

After cleaning the dataset, the next step is to uncover valuable insights. 

**Here’s a list of questions i found answers to by performing EDA: **
1. What racial groups are most impacted?
2. Which weapons are most commonly associated with reported cases?
3. What types of incidents are reported most frequently?
4. Which genre experiences the highest incidence of cases?
5. What age range is disproportionately affected?
6. When do incidents most commonly occur?
7. What are the statuses of the reported cases?
8. Which areas are considered the least safe?
9. On which weekday do we observe the highest number of reported cases?


<h4>Python libraries used:</h4>
<b>Pandas, Numpy, Matplotlib, Seaborn, Squarify</b>


<h4>Here you can find the datasets</h4>
https://drive.google.com/drive/folders/1mLX1MJrzldYg0O3IIs4zWWspgPPyvl5P?usp=sharing
