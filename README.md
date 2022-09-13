# RateMyResidential

A web application for viewing and rating/reviewing on-campus residential dorms and dining halls in UCLA. Built with React for the frontend and Firebase for the backend (database, user authentication, and hosting).

## How to Run the App:

Either:

Visit the Firebase-hosted web app link:
https://l-housing.web.app/

Or, clone the GitHub repository to your local machine and run a localhost of the web app. To do this, first make sure Node.js and Git are installed. Then, run the following commands in the terminal:
1) git clone https://github.com/nisukapalli/RateMyResidential.git
2) cd RateMyResidential
3) npm install
4) npm start

## Description

This app is a service for rating and reviewing on-campus housing and dining options at UCLA. Users are able to leave reviews in various categories, search for dorm buildings, and maintain a list of their preferred housing options. While platforms like Reddit have threads discussing UCLA's housing and dining options, they tend to be scattered across many posts, requiring students to search for specific questions they have. The purpose of this web app is to provide a consolidated location that facilitates finding and making reviews and ratings. RateMyResidential is inspired by Bruinwalk, a website that features anonymous student reviews of professors and classes at UCLA.

## Key Features

### 1. Display Dynamic Data to the User

Users will be able to view and add star ratings and text reviews. The ratings and number of reviews will change as more ratings/reviews come in, allowing a growing database to give more helpful advice to future students. Some pages will display different elements based on whether a user is logged in or not. Users who log in can generate multiple lists of preferred housing options.
    
### 2. Upload Data from Client to the Backend:

Ratings for dorms and dining halls uploaded by users will be saved in the application’s database along with written user reviews. The preferred housing lists created and modified by users will also be uploaded to and called from the database.
    
### 3. Meaningfully Search Through Server-Side Data: 

Users will be able to filter housing buildings by certain categories (accessibility to food, proximity to campus, parking, access to essentials, and noise level). Users can also look up specific dorms through the search bar, where clicking on a result takes the user to the building's page. Due to the smaller number of dining options, search results are only limited to dorm buildings. Moreover, searching for and making a list of preferred housing is more practical than doing so for dining options, as students can only live in one dorm building for the entire year but can eat at any dining hall they choose.
    
### 4. Unique Feature #1:

User profiles will be done with email/password authentication via Firebase authentication, which allows for individual students to keep a curated list of housing they like for ease of use in the app, and also prevents any flooding of the site by troll reviews, as users must have an account in order to leave a review. Any user, logged in or not, however, will be able to view the pages in this application.
    
### 5. Unique Feature #2:

Users will have a live text search that allows for searching specific housing buildings, this is done so that a student will not have to search through a list if they know exactly what they are looking for and can instead find directly what people think about a specific housing option. On the review side of the application, users can submit a text review, a review of ratings (i.e. rating from 1-5), or both for both housing and dining halls.
    
### 6. Unique Feature #3:  

Users will be able to save a list of preferred housing buildings under their user profiles, enabled by google authentication. Users can modify any list that they may have already created, adding or removing items from said list. They can also create new lists, and clicking on any housing name in the list will take the user to a new tab which navigates to that housing name's page.
