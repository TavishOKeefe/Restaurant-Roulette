# **Restaurant Roulette**
#####  C# .NET Core with MVC Group Project at Epicodus, 12/17/2018
##### Tavish OKeefe, Tanvi Garg, Sheila Stephen, Victoria Martinez, Ryan Leslie


## Description
A web application that takes out that takes the indecision out of your next eat out adventure. Created using C# .NET Core MVC setup with full CRUD functionality.

## Table of Contents
  1. [User Stories](#specs-work)
  2. [My SQL Database Setup](#db-setup)
  2. [Setup on OSX](#setup)
  3. [Technologies Used](#Tech-used)
  4. [MIT License](#mit-lic)


## User Stories <a name="specs-work"></a>
* User can login on the splash page or create a new user to login.
* User can view their current settings for the distance and price range for restaurants they want the app to choose from.
* User can go to the edit page and make new price and distance range selections
* User can now go back to their settings page and choose to roll using their current settings.
* For returning users, there is an option to roll from their saved list of restaurants from past uses.
* On rolling for a new restaurant, user can see the restaurant selected by the app.
* User can eat at the restaurant or roll again.
* Based on user experience, user can choose to add this restaurant to their favorites.
* Returning users now have the option to either roll dice from their favorites or let the app roll dice to select a new restaurant.


## Database Setup using SQL commands<a name="db-setup"></a>
* Production Database: `RestaurantRoulette.sql`
* Test Database: `RestaurantRoulette_Tests.sql`
* Tables in Database:  favorites, restaurant_data, users and users_favorites
* Join Table: users_favorites
* Relationship: One To Many

## Setup on Mac OSX<a name="setup"></a>
* Download and install .Net Core 1.1.4
* Download and install Mono
* Download and install MAMP 4.5
* Go to GitHub profile and clone the repo from [TanviCodeLife](https://github.com/TanviCodeLife/hair-salon.git). Use `git clone <project url>` command to pull it to a local repository in your Home directory.
* Open MAMP and start the Apache and MySql servers
* Navigate to MAMP > Tools > phpMyAdmin and import the RestaurantRoulette.sql file to create the database
* Navigate to MAMP > Tools > phpMyAdmin and import the RestaurantRoulette_Tests.sql file to create the test database
* Generate and add Google Maps API key to the project in RestaurantRoulette>>Views>>User>>All to the API call.
* Run `dotnet restore` from Main Project Folder (RestaurantRoulette) and Test Directory (RestaurantRoulette.Tests) to install packages
* Run `dotnet build` from Main Project Folder and make sure no build errors appear. Run `dotnet restore` after build is complete.
* Run `dotnet restore` to compile tests and then `dotnet test` from the Test Directory to run the testing suite. All tests should pass._
* Run `dotnet run` from Main Project Folder to start the server
* Wait till you see this message display in you bash terminal - "Now listening on: http://localhost:xxxx"
1* Copy the local host link http://localhost:xxx and paste it into your web browser address bar.
1* Browse through the project.

## Technologies Used<a name="Tech-used"></a>

* .Net Core 1.1.4
* MAMP 4.5 (phpMyAdmin)
* MySQL
* Bootstrap 3.3.7
* JavaScript
* jQuery 3.3.1

## License<a name="mit-lic"></a>

This software is licensed under the MIT license.

Copyright (c) 2018 **Tavish OKeefe**
