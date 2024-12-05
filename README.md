---

# Full Stack Developer Assignment

## Overview

Welcome to the Full Stack Developer assignment for Aasakya Digital Technologies Pvt Ltd. This test is designed to evaluate your skills in front-end and back-end development, including handling complex calculations, data manipulation, geolocation data, push notifications, and service workers. You have *2 days* to complete this assignment.

## Instructions

1. *Fork this repository* to your own GitHub account.
2. *Create a new branch* with your name (e.g., john-doe).
3. Complete the tasks outlined below.
4. *Submit a pull request* to this repository with your completed assignment.

## Tasks

### 1. Front-End Development

Create a simple web application using React.js that allows users to input data and view results. The application should include:

- A form to input data (e.g., user details, numerical data).
- Validation for the input fields.
- A table to display the input data.
- A button to calculate and display the results based on the input data.

### 2. Back-End Development

Develop a RESTful API using Node.js and Express.js that performs the following operations:

- *POST /data*: Accepts data from the front-end and stores it in a MongoDB database.
- *GET /data*: Retrieves all stored data.
- *GET /data/:id*: Retrieves data by ID.
- *PUT /data/:id*: Updates data by ID.
- *DELETE /data/:id*: Deletes data by ID.

### 3. Complex Calculations and Data Manipulation

Implement the following functions in the back-end to perform complex calculations and data manipulation:

#### a. Statistical Calculations

- *Calculate the average, median, and standard deviation* of numerical data stored in the database.
- Create an endpoint *GET /data/statistics* that returns these statistical values.

#### b. Data Aggregation and Filtering

- *Aggregate data* based on specific criteria (e.g., group data by a certain field and calculate the sum or average for each group).
- *Filter data* based on specific criteria (e.g., retrieve all records where a numerical field is above a certain threshold).
- Create an endpoint *GET /data/aggregate* that performs the aggregation and filtering and returns the results.

### 4. Geolocation Data and Mapping

Implement functionality to handle geolocation data and display it on a map:

- *POST /locations*: Accepts geolocation data (latitude and longitude) from the front-end and stores it in the database.
- *GET /locations*: Retrieves all stored geolocation data.
- *GET /locations/:id*: Retrieves geolocation data by ID.
- *PUT /locations/:id*: Updates geolocation data by ID.
- *DELETE /locations/:id*: Deletes geolocation data by ID.
- On the front-end, use a mapping library (e.g., Leaflet or Google Maps API) to display the geolocation data on a map.

### 5. Push Notifications and Service Workers

Implement functionality for push notifications and service workers:

- *Service Worker*: Set up a service worker to cache assets and enable offline functionality.
- *Push Notifications*: Implement push notifications to alert users about updates or important information.
- Create an endpoint *POST /subscribe* to handle push notification subscriptions.
- On the front-end, prompt users to subscribe to push notifications and handle the subscription process.

### 6. Complex Data Flows

Implement functionality to handle complex data flows from different points:

- Create a workflow that involves multiple steps and data transformations.
- For example, data entered in the front-end form should trigger a series of back-end processes, such as validation, transformation, and storage in different collections or databases.
- Ensure that the data flows are well-documented and that each step is clearly defined.

### 7. Documentation

Ensure your code is well-documented. Include comments and a brief explanation of your approach in the README file.

## Submission

1. Ensure your code is clean and well-organized.
2. Push your changes to your branch.
3. Create a pull request to the original repository.

## Evaluation Criteria

- Code quality and organization.
- Functionality and correctness of the application.
- Ability to handle complex calculations, data manipulation, geolocation data, push notifications, and service workers.
- Adherence to best practices and coding standards.
- Documentation and comments.

Good luck! If you have any questions, feel free to reach out.

---
