# Coding challenge
This Github repository consists of a coding challenge for various engineering roles at SpankChain. Should you be invited for another interview, you will have the opportunity to review and pair program this exact challenge (with your code) with a SpankChain engineering team member. 

# Purpose
Aim of these coding challenges is three fold,

- evaluate your coding abilities
- understand how you design a solution

# How you will be scored
You will be scored on,

- coding standard, comments and style
- overall solution design

# Instructions

- Please use JavaScript, NodeJS, ExpressJS, and a front-end library or framework of your choice (React, Angular, etc.) for the following challenge
- Candidate should put their test results on a public code repository hosted on Github
- Once test is completed please share the Github repository URL to Levi so he can review your work

# Challenge: Trail Management Web App

Create a simple web application to manage a list of trails.

## Details

- Use JavaScript, NodeJS, and ExpressJS to implement a basic CRUD API
  - Use any preferred tools to manage the database connection and schema (such as Knex, Sequelize, or TypeORM)
  - Trail data can be directly copy/pasted from [this array](https://gist.githubusercontent.com/pdubs/6df6ad3b3bb5640875fab5234dacdb30/raw/17ced06db226b9486dca46f18c8fe94f41887000/response.js)  
- Use any JavaScript front-end library or framework of your choice to implement a UI 

## Requirements

- API: CRUD endpoints for /trails route 
  - GET all trails
  - CRUD endpoints for individual trail by id
- UI: A simple list of trails and their information
  - List of all trails and their information

## UI Bonus (not required)

- Ability to filter by Elevation Gain 
- Creating New Trail & Delete Trail functionality in the UI
- Avoiding page reloads on form submits in the UI
- Using a CSS framework such as milligram or twitter bootstrap to standardize the UI
- A grid view of the trails with a thumbnail photo displayed in the UI

## API Bonus (not required)

- Supporting creation of many trails with one request in the API
- Creating additional endpoints that allow for unforeseen use cases in the API
