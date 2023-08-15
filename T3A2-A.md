# T3A2 - Full Stack App
### By Dieter Schmid, Wenxuan Pan, Alicia Han

## Table of Contents

1. [R1 Description of website](#r1-description-of-your-website)
2. [R2 Dataflow Diagram](#r2-dataflow-diagram)
3. [R3 Application Architecture Diagram](#r3-application-architecture-diagram)
4. [R4 User Stories](#r4-user-stories)

## R1 Description of your website

A digital School Yearbook that makes a record of all student in attendance at the particular year levels of the school.

### Purpose

To display a photo, contact information and the final year thoughts of students graduating the school. This becomes a permanent online record of all graduates of the school and it can be referred to by all stakeholders of the app.

### Functionality/Features

- The app will provide admin and students accounts with a login.
- The student can add themselves to the app.
- The student can update their details in the app.
- The student can remove themselves from the app.
- The student can upload a photo and display it.
- The student can fill out a questionnaire regarding their final thoughts.
- The student can provide contact details.

### Target Audience

This application is targetted at all school stakeholders this includes students of the graduating year level but also other students at the schools. It also includes allumi and parents of students at the school. Lastly it includes teachers and staff.

### Tech Stack

The application will utilise a MongoDB connected to a express.js server built on node.js. The front end of the application will use react.js html and css. The server and front end will be deployed to cloud services.

## R2 Dataflow Diagram

![Dataflow Diagram](./Docs/Dataflow%20Diagram.png)

## R3 Application Architecture Diagram

![Application Architecture Diagram](./Docs/Application%20Architecture%20Diagram.png)

## R4 User Stories

### Initial User Stories

1.	As an admin/student, I would like to be able to add a student profile into different classes/cohorts and year levels, so that student data is organised into the correct categories.
2.	As an admin/student, I would like to be able to login and view a list of students in each class and year level/cohort at my school.
3.	As an admin/student, I would like to be able to click into individual students and see their relevant information, so that I can stay in touch with my classmates and connect with acquaintances.
4.	As a student, I would like to be able to update my information, so that others can get in touch with me via my current contact details if needed, however I would like to ensure that only admin and myself can manipulate my account, for better security.
5.	As a student, I want to be able to delete any information on my account, or my entire profile, from the database so that I have control over my information.
6.	As an admin, I want to be able to remove any profile from the database to ensure data integrity.
7.	As an admin/student, I would like to have a navigation bar so that I can easily access different parts of the website.

### Revised User Stories to Reflect Updated Features

## R5 Wireframes

![Wireframe - Mobile](./Docs/Yearbook%20wireframes%20-%20mobile.png)

![Wireframe - Tablet](./Docs/Yearbook%20wireframes%20-%20tablet.png)

![Wireframe - Desktop](./Docs/Yearbook%20wireframes%20-%20desktop.png)

