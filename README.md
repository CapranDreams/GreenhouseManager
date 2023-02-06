# GreenhouseManager
Greenhouse sensor manager
This project is part of my University of St Thomas SEIS739 project
Group members:(1) Sasha Schrandt

This project aims to provide a UI for research on growing tropical fruit in Minnesota in a greenhouse environment. In particular, this greenhouse is researching methods for growing Hawaiian breadfruit to fruiting. There are traditionally a variety of factors that could lead to death of the tree or prevent it from fruiting in the first place.

Methods for using the data in this web interface to steer the growth and environment of the trees towards healthy include maintaining ideal weather and nutrients as well as the stretch-goal of using hourly imaging to train an AI/ML to observe the effects of conditions on the health of the plant. Similar techniques have been used (in my same greenhouse) to optimize the growth of strawberry plants (admittedly much easier) with surprising results on managing their environment. 

My learning goals along the way include integrating the SQL database with the sensor acquisition and html front end. Additionally, finding better ways to move AI models to the cloud for processing and learning how to automatically download fresh data for locally training the model will be useful to me in projects to come. I am not necessarily expecting any major success with the machine learning in this case, but you never know...

This project will use SQL to host the acquired sensor data and store images as used for the machine learning. Java will be used to handle all logic and control loops and handle data manipulations. HTML/CSS/JS/AJAX will be used for the UI.

A rough example of a real-time monitor is shown below:
![image](https://user-images.githubusercontent.com/6502745/216802459-e78688a2-1afa-4d65-af07-cf201d380355.png)
