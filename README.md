Background
The UK Food Standards Agency evaluates various establishments across the United Kingdom, and gives them a food hygiene rating. You've been contracted by the editors of a food magazine, Eat Safe, Love, to evaluate some of the ratings data in order to help their journalists and food critics decide where to focus future articles.

The NoSQL_setup.ipynb sets up and updates the database.

Part 1: Database and Jupyter Notebook Set Up

Part 2: Update the Database

  Added a new restaurant, Penang Flavours
  
  Updated the BusinessTypeID for the new restaurant
  
  Removed establishments in Dover that we were not interseted in
  
  Converted latitude & longitude to decimal numbers and converted RatingValue to integer numbers
  

Part 3: Exploratory Analysis

1. Which establishments have a hygiene score equal to 20?
   
There are 41 establishments with a hygiene score equal to 20.

2. Which establishments in London have a RatingValue greater than or equal to 4?
   
There are 33 establishments in London that have a RatingValue greater than or equal to 4.

3. What are the top 5 establishments with a RatingValue of 5, sorted by lowest hygiene score, nearest to the new restaurant added, "Penang Flavours"?

The top 5 establishments that fit this criteria are:
  Iceland
  Atlantic Fish Bar
  Plumstead Manor Nursery
  Howe and Co Fish & Chips - Van 17
  Volunteer

4. How many establishments in each Local Authority area have a hygiene score of 0? Sort the results from highest to lowest, and print out the top ten local authority areas.
   
![NoSQL Pic](https://github.com/margoberry17/12-NoSQL-Establishments/assets/136475202/f3164652-53ad-4fdf-a9d7-8c6d8fceca08)


