## Contact Information

Name: Daniel Scislowski
Email: daniel.j.scislowski@gmail.com
LinkedIn profile: www.linkedin.com/in/daniel-scislowski-2bb3782ba
Github profile: https://github.com/MrScislowski

## Objective statement

For the past 12 years I have been a high school computer science / math teacher, and would like to transition to a role in data science or software development. I am a lifelong learner, and have enjoyed the challenge of connecting high school math/science content to more advanced applications in physics, algorithms, and other familiar fields. But the most rewarding part of my job has been analyzing performance data and streamlining workflows using the analytical skills and experience I developed during my time in college and graduate school. I would like to transition to a career where I can apply and hone those skills in more depth.

## Education

### MSc (physics) from University of Washington, 2008-2011

As a research assistant working on the SNO+ neutrino observation experiment, I worked on simulating neutrino and background radiation detection in liquid scintillator using the Geant4 particle physics software toolkit.

### BSc (physics) from University of Manchester, 2004-2008

Capstone projects consisted of:

- Writing C code (using Runge-Kutta method to solve Schrodinger equation) to generate theoretical scattering cross sections for one-pion exchange model, and compare to experimental data
- Writing shell scripts to analyze and visualize the performance of several distributed data storage methods for the Large Hadron Collider at CERN

## Experience

### High School Math Computer Science Teacher, Wichita area high schools, 2012-present

- Taught computer science, physics, and math classes including AP Computer Science A and AP Calculus (consistently scoring above national and Kansas averages in AP exam scores)
- Collected data and performed analysis on academic performance, attendance data, and remote learning engagement patterns (using SQLite and firebase databases, coding in R and python)
- Scraped and categorized content from a variety of sources (including College Board, Khan Academy) to streamline accessibility
- Developed a full stack web app for use by teachers and students to facilitate equitable access to classroom assistance (using react, express, and mongoDB)

## Technical Projects

### HWData (SQL, R w/ tidyverse), 2019

Kept math class grades in SQLite database, and used R markdown files to:

- make a graphical summary of each student's performance over the semester to look for notable improvements / performance decreases
- determine the correlation between quiz scores, homework completion, and test scores
- determine the days of the week students are missing assignments most, and student responses to missing class (e.g. on cloud learning platform)

### APCalculusResourceOrganizer, 2019

Gathered data with manual screenshot of past AP tests, scraping Khan Academy exercises, and scraping AP classroom website. Using this:

- analyzed which topics were tested most in recent AP tests, and kept track of how much practice on each topic I had assigned
- generated large question bank html document that allowed quick and easy access to all the available content, and to track what I had used already
- generated individualized student study plans and class summary data using AP Practic exam performance data

### InfiniteCampus, 2020

School was implementing experimental policy of "flex days" where students could choose which classes to visit and scan their student ID barcode to log attendance. However, attendance data was hard to access through student information system (SIS). I used R to analyze all of the attendance data and:

- identified problems in data integrity and proposed changes to real-time scanning interface
- generated graphical display for each students flex day location that was more user friendly than provided by SIS

### Video Administration, 2021

In the 2020-2021 year when my school district was using hybrid learning, I hosted lesson videos on a Google Site with an embedded iframe that was able to log student interactions to a firebase database. I used python with pandas to compare in-person to remote instruction, and visualized metrics like what time of day students were engaging with instruction on remote days.

### ap-physics-question-bank

I scraped screenshots of AP Physics exam questions, and categorized their topics in a spreadsheet. I hosted this information on a React [website](https://ap-physics-question-bank.herokuapp.com/) that allows searching for exam questions by topic, by year, or by text (I put each question screenshot through tesseract OCR). This facilitates quick access to practice material.

### student-help-queue

Wrote a full stack [web app](https://help-queue-teacher-frontend-239b686a3dfd.herokuapp.com/) (react, node with express, mongoDB) for students and their teacher to use. Acts like a ticketing system where students add their name to a queue when they want help in class, ensuring equitable assistance by teacher and monitoring how long wait times are, as well as preserving requests spanning days. Used this in the 2023-2024 school year.

## Professional Development

Audited [University of Helsinki Full Stack Open](https://fullstackopen.com/en/#course-contents) Course (parts 0-11 covering React, Express, testing, React state management, GraphQL, Typescript, and React Native). Currently working on credentializing this.
