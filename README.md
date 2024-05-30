# Study Club Repository
![principal](https://github.com/AnndyyRobles/DjangoDiscordBasedWebApp/blob/master/imgs/img1.jpg)
## Overview
Study Club Repository is a Discord-based web application where users can create rooms, send messages, and tag them with different topics. It allows users to log in to use the application, facilitating study group discussions and topic-based conversations.

## Features
Create Rooms: Users can create rooms for different topics.
Messaging: Send and receive messages within rooms.
Tagging: Tag messages with different topics for better organization.
User Authentication: Secure user login and registration

## Installation
Prerequisites
Python 3.x
pip (Python package installer)
Virtualenv (recommended)


## Setup
### Clone the repository:
```branch
git clone https://github.com/AnndyyRobles/DjangoDiscordBasedWebApp.git
cd DjangoDiscordBasedWebApp
```
### Create and activate a virtual environment:
```branch
python -m venv venv
source venv/bin/activate   # On Windows use `venv\Scripts\activate`
```

### Install the dependencies:
```branch
pip install -r requirements.txt
```
### Apply migrations:
```branch
python manage.py migrate
```
### Create a superuser (optional but recommended for accessing the admin panel):
```branch
python manage.py createsuperuser
```
### Run the development server:
```branch
python manage.py runserver
```
### Open your browser and go to http://127.0.0.1:8000/ to see the application in action.
![about](https://github.com/AnndyyRobles/DjangoDiscordBasedWebApp/blob/master/imgs/img3.jpg)
## Usage
Creating Rooms: Log in and click on "Create Room" to start a new discussion room.
Sending Messages: Enter a room and start sending messages to other participants.
Tagging Messages: Use tags to organize messages by topics.
Recent Activities: View recent activities and interactions on the right sidebar.
![user](https://github.com/AnndyyRobles/DjangoDiscordBasedWebApp/blob/master/imgs/img2.jpg)
## Acknowledgments
Developed by Andres Zahir Rodriguez Robles.
![messages](https://github.com/AnndyyRobles/DjangoDiscordBasedWebApp/blob/master/imgs/img4.jpg)
