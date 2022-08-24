# Track - Expense Tracker Application (Frontend Repository)
Track is an expense tracker that enables collaboration between people when budgeting. Track was submitted for the 2022 HackThe6ix hackathon, gaining the "Best Beginner Hack" award.

Backend Repo : https://github.com/saad1035/TrackUI-HT622 </br>
DevPost : https://devpost.com/software/track-pwrn7y

Developped with love during HackThe6ix '22

<p align="left">
  <img src="https://d112y698adiu2z.cloudfront.net/photos/production/software_thumbnail_photos/002/195/143/datas/medium.gif">
</p>

# Inspiration

- Many individuals lack financial freedom, and this stems from poor spending skills. As a result, our group wanted to create something to help prevent that. We realized how difficult it can be to track the expenses of each individual person in a family. As humans, we tend to lose track of what we purchase and spend money on. Inspired, we wanted to create an app that stops all that by allowing individuals to strengthen their organization and budgeting skills.

# What It Does

- Track is an expense tracker website targeting households and individuals with the aim of easing people’s lives while also allowing them to gain essential skills. Imagine not having to worry about tracking your expenses all while learning how to budget and be well organized.

- The website has two key components:

  - Family Expense Tracker:
The family expense tracker is the ```main dashboard``` for all users. It showcases each individual family member’s total expenses while also displaying the expenses through categories. Both members and owners of the family can access this screen. Members can be added to the owner’s family via a household key which is only given access to the owner of the family. Permissions vary between both members and owners. Owners gain access to each individual’s personal expense tracker, while members have only access to their own personal expense tracker.

  - Personal Expense Tracker:
The personal expense tracker is assigned to each user, displaying their own expenses. Users are allowed to look at past expenses from the start of the account to the present time. They are also allowed to add expenses with a click of a button.

# How We Built It

- Utilized the MERN (MongoDB, Express, React, Node) stack
- Restful APIs were built using Node and Express which were integrated with a MongoDB database
- The Frontend was built with the use of vanilla React and Tailwind CSS

# Challenges We Ran Into
- Frontend: 
  - Connecting EmailJS to the help form 
  - Retrieving specific data from the backend and displaying pop-ups accordingly 
  - Keeping the theme consistent while also ensuring that the layout and dimensions didn’t overlap or wrap 
  - Creating hover animations for buttons and messages

- Backend: 
  - Embedded objects were not being correctly updated 
  - Needed to learn about storing references to objects and populating the references 
  - Designing the backend based on frontend requirements and the overall goal of the website

# Accomplishments We’re Proud Of

- As this was all of our’s first or second hackathons we are proud to have created a functioning website with a fully integrated front and back-end.
- We are glad to have successfully implemented pop-ups for each individual expense category that displays past expenses.
- Overall, we are proud of ourselves for being able to create a product that can be used in our day-to-day lives in a short period of time.

# What We Learned

- How to properly use embedded objects so that any changes to the object are reflected wherever the object is embedded
- Using the state hook in ReactJS
- Successfully and effectively using React Routers
- How to work together virtually. It allowed us to not only gain hard skills but also enhance our soft skills such as teamwork and communication.

# What’s Next For Track

- Implement an income tracker section allowing the user to get a bigger picture of their overall net income
- Be able to edit and delete both expenses and users
- Store historical data to allow the use of data analysis graphs to provide predictions and recommendations.
- Allow users to create their own categories rather than the assigned ones
- Setting up different levels of permission to allow people to view other family member’s usage

<p align="center">
  <h3><strong>Landing Page</strong></h3>
  
  ![original (1)](https://user-images.githubusercontent.com/81185080/186354434-8f963e6d-22ea-4112-8279-89e6dd0d5821.png)

  <h3><strong>Personal Dashboard</strong></h3>
  
  ![original (1) (1)](https://user-images.githubusercontent.com/81185080/186354542-878eb701-930a-463b-9b7e-7f8e1fc16abb.png)

  <h3><strong>Dashboard</strong><h3>
  
  ![original (2)](https://user-images.githubusercontent.com/81185080/186354567-e8bcaec5-96ac-42b0-85bb-3d2c0000463f.png)

  <h3><strong>Add Expenses</strong></h3>
  
  ![original (3)](https://user-images.githubusercontent.com/81185080/186354615-7e1abec0-bd42-4899-a50a-423b13f10c7c.png)

  <h3><strong>Contact Page</strong></h3>
  
  ![original (4)](https://user-images.githubusercontent.com/81185080/186354649-d3a20ae5-814e-4568-931f-a4ef881b9232.png)

</p>
