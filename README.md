# Family Travel Tracker App

# Description
 The Family Travel Tracker App is a web-based application created to assist families in recording the countries they have visited. Users can add new destinations to their travel log, view the total number of countries they've visited, and switch between different family members to see each person's individual travel history.

 # Features

- Add Visited Countries: Users can enter the name of a country to add it to their list of visited places.
- Check Visited Countries: Users can see a list of the countries they have visited, along with the total count.
- Switch between Users: Users can switch between different family members to view each person's individual travel records.
- Add New Family Member: Users can add new family members to track their travel histories.

# Technologies Used

- Express: Used to build the web server and manage routing.
- Body-parser: Middleware for parsing incoming request bodies.
- pg: PostgreSQL client for Node.js.
- EJS: Embedded JavaScript templates for rendering HTML pages.
- HTML/CSS: Applied for frontend design and styling.
- PostgreSQL: Database management system for storing user data and visited countries.

# Installation

- Clown the current repository:
  [git clown https://github.com/SaikrishnaSamudrala3/Family-Travel-Tracker]
- Install Node.js and npm if they are not already installed.  
- Install PostgreSQL and create a database named 'world'.
- Install dependencies:
  [npm i]

# Instructions to setup
-start the server using:
[npm start]
- Access the web appilcation through your local host 3000
  
# Setting up the database
- Make sure PostgreSQL is installed and running.  
- Connect to PostgreSQL and create a database named 'world'.  
- Execute the provided SQL script (schema.sql) from the repository to create the necessary tables.

# How to Use
- When you access the application, you will see a list of visited countries for the current user along with the total count.  
- You can switch between different family members using the dropdown menu.  
- To add a new visited country, enter the country name in the input field and click 'Add'.  
- To add a new family member, click the 'Add New Member' button, enter the name, select a color, and then click 'Submit'.
