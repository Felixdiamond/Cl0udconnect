# Cl0udConnect

Cl0udConnect is a video conferencing app built with Django. With Cl0udConnect, users can sign up, log in, and share meeting links to conduct video conferences with others. This app provides all the necessary features you'd expect from a competent conferencing app.

## Features

- User authentication: Users can create an account and log in to access the app's features.
- Meeting creation: Users can create a new meeting and generate a unique link to share with other participants.
- Joining meetings: Participants can join a meeting by clicking on the link shared by the meeting host.
- Video and audio conferencing: Participants can communicate with each other using video and audio conferencing.
- Screen sharing: Participants can share their screens with others during the meeting.
- Chat: Participants can use the chat feature to send text messages to other participants.
- Recording: Meetings can be recorded and saved for future reference.

## Installation

To install Cl0udConnect, follow these steps:

1. Clone the repository to your local machine: git clone https://github.com/Felixdiamond/Cl0udconnect.git
2. Create a virtual environment and activate it:
   ```bash
   python -m venv env
   source env/bin/activate
   ```
3. Install the dependencies:
    ```bash
    pip install -r requirements.txt
    ```
4. Run the migrations:
    ```bash
    python manage.py migrate
    ```
5. Run the development server:
    ```bash
    python manage.py runserver
    ```
6. Access the app in your web browser at `http://localhost:8000/`.

## Usage

To use Cl0udConnect, follow these steps:

1. Create an account or log in to an existing account.
2. Create a new meeting and copy the unique link.
3. Share the link with other participants.
4. Join the meeting by clicking on the link.
5. Use the video, audio, screen sharing, and chat features to communicate with other participants.
6. End the meeting and optionally save the recording for future reference.

## Contributing

If you'd like to contribute to Cl0udConnect, please follow these steps:

1. Fork the repository to your own GitHub account.
2. Create a new branch from the `main` branch.
3. Make your changes and commit them to your branch.
4. Push your branch to your forked repository.
5. Create a pull request from your branch to the `main` branch of the original repository.


## Credits

Cl0udConnect was created by [Felix Dawodu](https://github.com/Felixdiamond).
