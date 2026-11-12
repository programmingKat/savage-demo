# Savage Demo

A 21 Savage-themed message board where anyone can post a message and give it a thumbs up.

## Goal

* I built this to practice full-stack CRUD with Express and MongoDB. 
* Visitors post a message with their name, and each message is saved to the database and rendered with EJS. 
* Messages can be voted up or down or deleted, and I added a sort to the message list.

## Tech Stack

- **Front end:** EJS templates, CSS, JavaScript (Fetch API), Font Awesome icons
- **Back end:** Node.js, Express
- **Database:** MongoDB (native driver)
- **Hosting:** [Render]

## How to Use Online 
1. Open the [live app](https://savage-demo-t7g4.onrender.com/).
2. Enter your name and a message, then click **Submit**.
3. Use the thumbs-up and thumbs-down icons to raise or lower a message's score, or the trash icon to delete it.

## Installation

1. Clone repo
2. run `npm install`
3. No `.env` file is needed. The server runs on port 3000, and the MongoDB connection string is in `server.js`.

## Usage

1. run `npm run savage`
2. Navigate to `localhost:3000`


| Messages | Adding a Message |
<img width="1200" height="527" alt="image" src="https://github.com/user-attachments/assets/8823c47a-477e-4920-830f-aefccb908058" />


## Future Improvements

- Sort messages by `thumbUp`, since the current sort uses a `likes` field that messages do not have
- Move the MongoDB connection string into a `.env` file
- Track thumbs down as its own count instead of subtracting from the thumbs up total
