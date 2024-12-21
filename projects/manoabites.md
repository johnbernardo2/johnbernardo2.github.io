---
layout: project
type: project
image: img/ManoaBitesLogo.png
title: "Manoa Bites"
date: 2024
published: true
labels:
  - Typescript
  - HTML/CSS
  - Bootstap 5
  - GitHub
  - PostgreSQL
  - Prisma
  - React
summary: "A responsive web application for travel planning that my team developed in ICS 314."
---

<img class="img-fluid" src="../img/vacay/vacay-home-page.png">

Manoa Bites is a web application designed to help students and staff at the University of Hawaiʻi at Mānoa easily navigate food options on campus. The app consolidates menu information, provides tailored recommendations, and allows vendors to update their offerings in real-time. Key features include:

1. Campus-Wide Food Directory: A centralized hub for food options, including Campus Center, food trucks, and other locations.
2. Real-Time Updates: Vendors can log in to update daily menus, ensuring accurate and up-to-date information.
3. Personalized Recommendations: Users can set preferences to receive suggestions tailored to their tastes.
4. Role-Based Access: Differentiated access for Users, Vendors, and Admins for a streamlined experience.

## My Role and Contributions
In this collaborative project, I played a key role in implementing two major features:

1. Page Routing and Form Functionality:

- Designed and implemented the signup and login pages with email and password functionality.

- Added an optional "Signup Key" field for role-based access. By using keys stored in an .env file, users could register as Vendors or Admins if they entered the correct key during signup. For example, entering "man-bites-admin" would assign an Admin role to the account.
2. Dynamic Map Markers with Google Maps API:

- Integrated Google Maps API to display dynamic markers for food locations on campus.

- Designed functionality to fetch restaurant data (latitude and longitude) upon page load and populate map pins dynamically.

- Enhanced the user experience by including interactive info windows for each marker, detailing restaurant names and menu items.

- Overcame technical challenges, such as resolving a bug that restricted marker updates to within a one-integer range of their original coordinates. This required a combination of AI tools like ChatGPT and manual debugging using online resources.

## Challenges and Lessons Learned
Implementing dynamic map markers was a particularly rewarding yet challenging aspect of this project. While AI tools like ChatGPT provided guidance on setting up the Google Maps API, debugging edge cases required manual research and problem-solving. For example, a persistent bug with marker updates was resolved with a simple two-line code change discovered through a Google search, underscoring the importance of combining AI assistance with independent research and critical thinking.

Additionally, this project deepened my understanding of tools like Prisma and PostgreSQL. Prisma served as the schema intermediary, while PostgreSQL managed user data, including roles, email addresses, and preferences. Working on the project highlighted areas for further learning, particularly regarding database design and API optimization.

## Reflections
This project was not just about building a functional application; it was a hands-on introduction to the complexities of software engineering, including collaborative development, real-time problem-solving, and user-centric design. I gained a clearer understanding of the importance of efficient workflows, robust debugging practices, and integrating diverse tools into cohesive systems.
{% gist 9defa1fb3f4eb593ba5fa9eacedca960 %}
 
Source: <a href="https://github.com/theVacay/vacay">theVacay/vacay</a>
