---
title: "Find Your Dream Job"
date: 2020-07-13T13:06:26+06:00
featureImage: images/allpost/fydj_1.png
postImage: images/single-blog/fydj_1.png
tags: NLP
# categories: documentation
---
### The solution we built
For the final project of my Data Science Bootcamp, my team and I created an app designed to empower new commers navigating the Data Science job market. Our app provides: 

1) **A bird's eye view of the job market** with statistics on: <br>
    - in-demand positions <br>
    - top hiring companies <br>
    - most desired skills <br>

2) **Enhanced Skill Insights**: users can input a skill and receive related skills frequently mentioned together in job listings.

3) **Tailored Job Recommendations**: Users can paste a job listing they like and receive similar positions. 


### Under the hood
- **Building the dataset**: we scraped job listings from Indeed.com, enriching it with a dataset from Kaggle. <br>
- **Market insights**: we employed advanced NLP techniques and Word2Vec model provide accurate job market insights. <br>
- **Find a similar job**: I personally developed this feature, by leveraging the power of Doc2Vec model and text similarity. <br>
- **Deployment**: the models were served through an API, providing a seamless experience on our Streamlit webpage.<br>

{{< blogsection image="images/single-blog/fydj_2.png" >}}
{{< /blogsection >}}