# ZTM-ML-Notes
Notes on Daniel Bourke + Andrei Neagoi's ML Course. 

## 1) Machine Learning 101

### i. What is the goal of Machine Learning? 

**Computers** were brought into this world to make completing tasks more efficient for humans. 

The goal of **machine learning** is to make computers act more and more like humans. The more they act like humans, the more helpful they are for humans! 

### ii. AI/Machine Learning/Data Science

**Artificial Intelligence** - human intelligence exhibited by machines.

**Narrow AI** - Machines can be just as good or even better than humans at certain tasks. Ex: detecting heart disease, playing chess, etc. Narrow AI is only good at one specific task extremely well. 

**Artifical General Intelligence (AGI)** - Extremely good at many human tasks (we are approaching this era soon)

**Machine Learning** -  a subset of AI. It's an approach to try and achieve AI through systems that want to find patterns through a set of data. Computers can do things without us saying, "do this, then do that". Stanford describes ML as the science of getting machines to act without humans specifying instructions. 

**Deep Learning** - Techniques for implementing machine learning. (also: deep neural networks)

**Data Science** - Simply put, analyzing data. There's a lot of overlap w. ML. 

### iii. Machine Learning Playground Exercise: https://teachablemachine.withgoogle.com/

### iv. How did we get to Machine Learning? 
(Simplified version) We first used spreadsheets like excel to generate data and put it in an excel file to make business decisions. As companies got more idea, we created this idea of relational databases. We needed a better way to organize and understand things from data. Thus, came MySQL: this helped us read, write, and understand data of many different types. Then, in 2000s, we created this idea of "big data" since FB, Google, Twitter needed to store way more precise data for their customers. Then after, NoSQL + MongoDB came along to help us manage even more meta data. 

Machine Learning came along to automate and help us make data-driven decisions more efficiently. This was due to the growth in data and the improvements of CPU, GPU, and computation. 

Project Path: ![Project Path](https://cloud-qumfiry5u.vercel.app/0screen_shot_2020-10-22_at_6.49.40_pm.png)

### v. Oversimplified YouTube Recommendation Model: https://ml-playground.com/#

Data points: ![Data Points](https://storage.googleapis.com/file-in.appspot.com/files/aRZ-GJHqkD.png)

### vi. Types of Machine Learning

Different types:![Different Types](https://cloud-3xmjrbr9p.vercel.app/0screen_shot_2020-10-22_at_7.42.56_pm.png)

**Supervised Learning** - Pre-created categorizations for data. You can do things like classification: (is this an apple or a pear?) (regression, stock prices, etc).

**Unsuperized Learning** - Data that doesn't have labels / groups don't exist. _Clustering_ means we need machine to create these groups. 

**Reinforcement Learning** - Teaching machines through trial and error. It learns after trialing with data many times. This is seen in skill acquisition like playing chess.  

All these processes are trying to do are ultimately get better at predicting. 

## 2) ML and Data Science Framework 

Machine Learning comes in three parts: data modeling, data collection, and deployment. 

First, create a framework. Then, match it to DS and ML tools. Lastly, we'll learn by doing. 

1) Determine what problem we're trying to solve. (supervised or unsupervised)
2) What kind of data do we have? (structured or unstructured?)
3) What does success mean to us? (metrics in where we want our models to be at of an accuracy - somethimg to aim for). 
4) Features - which ones are most useful? Bodyweight is a numerical feature (ex: they're more likely to have heart disease. A ML model algorithm's goal is to turn this data into specific people. 
5) Modeling - Based on our problem and data, which model should we use."
6) Experimentation - how can we improve? what can we try next?

### i. Types of ML Problems 

First, we should clarify for what types of problems we don't need ML to solve (since AI isn't the answer to everything): when a simple hand-coded instruction-based systen will work. For example, if you want to create your favorite dish, if you already know what you need in order to create the result and how to get there, you shouldn't and it wouldn't make sense to use ML to gather the processes. 

Main types of machine learning: supervised learning, unsupervised learning, transfer learning, reinforced learning. These are the most common. 

Transfer learning is when a machine is learning what another machine knows. 

Learning types:![Learning Types](https://storage.googleapis.com/file-in.appspot.com/files/rewmCPZnIK.png)

### ii. Types of Data 

**Structured data** - what we see in an excel file, such as rows and columns of different features and records. 

**Unstructured data** - images, natural language text, transcribed phone calls, video calls, etc. 

Data types:![Data Types](https://storage.googleapis.com/file-in.appspot.com/files/xveUATERuo.png)

**Static Data** - Data that doesn't change over time. CSV is one of the most common types of data formats. 

Static Data:![Static Data](https://storage.googleapis.com/file-in.appspot.com/files/ZNxQVPBnq_.png)

**Streaming Data** - Data that changes over times. For example, say you wanted to predict how stock prices change depending on news headlines, you'd be working with streaming data since news headlines update constantly. Most of the work you do in practice will start with static data. But once your efforts show more results and you learn, you'll soon be working with streaming data. 

Streaming Data:![Streaming Data]https://storage.googleapis.com/file-in.appspot.com/files/6r3dy5LJpz.png)


