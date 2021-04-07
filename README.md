# EC500_P2P_Chat

| Collaborators               |
| --------------------------- |
| Ben Leone (bleone90@bu.edu) |

## MVP

- Register yourself in the app to become discoverable to other users.
- Send a message to those you want to connect with to establish a session.
- For users who are offline, sending a message stores the message locally to be sent when other user comes online.
- All passwords and messages are hashed to be decrypted by other user.

## Setup

- Clone and `cd` into repository
- `python3 -m venv venv`
- `source venv/bin/activate`
- `pip3 install -r requirements.txt`
- `python3 server.py`
- Run `python3 client.py` in two seperate terminal windows
- Enter the host IP and port number of other client and chat!

## Modules

- User Interface
- Login
- Database
- Security/Encryption
  - Socketing

## Technologies Used

- Application: Python
- Database: SQLite
