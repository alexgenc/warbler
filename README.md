# warbler
This project is intended to create a somewhat-functioning [Twitter](https://twitter.com/?lang=en) clone that has all the basic Twitter functionalities. 

## Introduction
This application was built with the purpose of getting more experience with Python framework Flask and SQLAlchemy.

![Warbler.jpg](https://i.postimg.cc/rwTqZzY2/Warbler.jpg)

Live Demo: https://alexgenc-warbler.herokuapp.com/

## Features

- Sign Up
- Sign In
- View Other User's Profiles
- Follow/Unfollow Other Users
- Post Tweet / Delete Tweet
- Favorite/Unfavorite Tweets
- Search For Users & Tweets
- Update User Information
- Update Password
- Delete User Account

## Technologies

Here is a list of technologies used:

- HTML
- CSS
- JavaScript
- Ajax
- Python
- Flask
- Jinja
- WTForms
- PostgreSQL
- SQLAlchemy

## Testing
There are a total of 4 test files. 2 for model tests, 2 for view tests.

- test_message_model.py - Test message instances and all message related functionalities.
- test_user_model.py - Test user registration, user login, invalid registration and login cases, changing password, and more.
- test_message_views.py - Test if message related routes display as intended.
- test_user_views.py - Test if user related routes display as intended.
