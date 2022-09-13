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

Users are able to filter housing buildings by certain categories (accessibility to food, proximity to campus, parking, access to essentials, and noise level). Users can also look up specific dorms through the search bar, where clicking on a result takes the user to the building's page. Due to the smaller number of dining options, search results are only limited to dorm buildings. Moreover, searching for and making a list of preferred housing is more practical than doing so for dining options, as students can only live in one dorm building for the entire year but can eat at any dining hall they choose.
    
### 4. Unique Feature #1:

User profiles are created and accessed with email/password authentication via Firebase authentication. Visiting the app with a profile allows students to keep a curated list of housing they like for ease of use. In addition, users must have an account in order to leave a review, which prevents any flooding of the site by troll reviews. However, any user, logged in or not, will be able to view the ratings and reviews.
    
### 5. Unique Feature #2:

Users have access to a live text search that allows them to search for specific housing buildings. This makes it easier for users to find a particular page, instead of having to search through their created lists to visit the page they want. Users can also submit a star rating from 1-5 and a text review for any housing or dining option.
    
### 6. Unique Feature #3:  

Users are able to save a list of preferred housing buildings under their user profiles, enabled by Google authentication. Users can create new lists or modify existing ones. Clicking on any housing name in the list will take the user to a new tab which navigates to that dorm building's page.
