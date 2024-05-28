# Study Club Repository
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
git clone https://github.com/AnndyyRobles/DjangoDiscordBasedWebApp.git
cd DjangoDiscordBasedWebApp

### Create and activate a virtual environment:
python -m venv venv
source venv/bin/activate   # On Windows use `venv\Scripts\activate`


### Install the dependencies:
pip install -r requirements.txt

### Apply migrations:
python manage.py migrate

### Create a superuser (optional but recommended for accessing the admin panel):
python manage.py createsuperuser

### Run the development server:
python manage.py runserver

### Open your browser and go to http://127.0.0.1:8000/ to see the application in action.

## Usage
Creating Rooms: Log in and click on "Create Room" to start a new discussion room.
Sending Messages: Enter a room and start sending messages to other participants.
Tagging Messages: Use tags to organize messages by topics.
Recent Activities: View recent activities and interactions on the right sidebar.

## Acknowledgments
Developed by Andres Zahir Rodriguez Robles.
