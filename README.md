# Real-Time Chat Application

This is a real-time chat application built with Django. It allows users to communicate with each other in real-time through a web interface.

## Features

- Real-time messaging: Users can send and receive messages instantly using WebSocket.
- User authentication: Secure login and registration system.
- Chat rooms: Users can create and join multiple chat rooms.
- User profiles: Users can update their profile information.
- Responsive design: Works on both desktop and mobile devices.

## WebSocket Integration

This project uses WebSocket to enable real-time messaging between users. WebSocket allows for full-duplex communication channels over a single TCP connection, making it ideal for real-time applications like chat.

## Clone the project

```
https://github.com/rakesh-sangode/realtime-chat.git
```

## Setup

### Create Virtual Environment

#### Mac

```
python3 -m venv venv
source venv/bin/activate
```

#### Windows

```
python3 -m venv venv
.\venv\Scripts\activate.bat
```

### Install dependencies

```
pip install --upgrade pip
pip install -r requirements.txt
```

### Migrate to database

```
python manage.py migrate
python manage.py createsuperuser
```

### Run application

```
python manage.py runserver
```
