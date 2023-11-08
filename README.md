# Team-Chat Application

**Team-Chat** is a dynamic and feature-rich platform designed for real-time communication. It offers the core features of chat and voice communication platforms and is suitable for both personal and professional use.

**Live App:** [Team-Chat App](https://team-chat-app-production-d0f2.up.railway.app)

![Screenshot](/path/to/screenshot.png)

## Table of Contents

- [Overview](#overview)
- [Key Features](#key-features)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)


## Key Features

- **Real-time Messaging**: Utilizes Socket.io to provide real-time messaging capabilities, allowing users to communicate seamlessly.
- **Attachment Support**: Users can send attachments as messages using the UploadThing library.
- **Message Editing and Deletion**: Messages can be edited and deleted in real time, ensuring a dynamic and responsive chat experience for all users.
- **Text, Audio, and Video Call Channels**: Create and join channels for text, audio, and video calls, enabling various forms of communication.
- **1:1 Conversations**: Initiate private one-on-one conversations between members for more personalized interactions.
- **1:1 Video Calls**: Enjoy video calls with other members for face-to-face communication.
- **Member Management**: Admins can kick members and change their roles, allowing for effective server management.
- **Invite System**: Generate unique invite links and a fully functional invite system to bring new members on board.
- **Infinite Message Loading**: Utilizes `@tanstack/query` to load messages in batches of 10, ensuring efficient message retrieval.
- **Server Creation and Customization**: Users can create their own servers and customize them to suit their preferences.
- **Beautiful UI**: The application boasts an attractive user interface, designed with TailwindCSS and ShadcnUI for a visually appealing and user-friendly experience.
- **Responsiveness**: The application is fully responsive and provides an optimal user interface on both desktop and mobile devices.
- **Light/Dark Mode**: Users can switch between light and dark modes to personalize their experience.
- **Websocket Fallback**: In case of issues with Websockets, the application falls back to polling with alerts to maintain communication.
- **ORM and Database**: Utilizes Prisma as the ORM and stores data in a MySQL database hosted on Planetscale.
- **Authentication**: Users can securely log in and interact with the application using authentication provided by Clerk.


## Technologies Used

The "Team-Chat" application leverages a range of modern web development technologies, including:

- Socket.io
- UploadThing
- @tanstack/query
- TailwindCSS and ShadcnUI
- Prisma
- MySQL database using Planetscale
- Authentication with Clerk

## Installation and Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/khatiazitanishvili/team-chat-app

2. Navigate to the project directory: `cd team-chat-app`
3. Install dependencies: `npm install`
4. Start the development server: `npm run dev`


