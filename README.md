# ShareGen Microblogging Platform

ShareGen is a cutting-edge microblogging platform designed to deliver a high-performance and scalable experience for users. Built with Next.js, Node.js, Gemini AI, and MongoDB, ShareGen leverages advanced features to enhance user engagement and streamline content creation.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [Community](#community)
- [License](#license)

## Introduction

Welcome to ShareGen! This platform offers dynamic content creation and seamless community interactions, providing an innovative solution for microblogging. Explore the source code, contribute, and customize ShareGen to suit your needs.

## Features

- **Dynamic Content Creation**: Utilize Gemini AI to generate and share posts with AI-driven responses.
- **Real-time Updates**: Implement webhooks to receive instant notifications and handle real-time events.
- **User Authentication**: Manage user accounts and profiles securely with Clerk, supporting email, password, and social logins.
- **Scalable Architecture**: Built on Next.js and Node.js for enhanced performance and scalability.
- **Data Management**: Efficiently handle complex data schemas and large datasets using MongoDB.
- **Responsive UI/UX**: Enjoy a modern, responsive design crafted with Tailwind CSS for an optimal user experience.

## Tech Stack

- **Frontend**: Next.js, Tailwind CSS
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **AI Integration**: Gemini AI
- **Authentication**: Clerk
- **Additional Technologies**: Webhooks, JavaScript (ES6+), TypeScript

## Installation

To set up ShareGen locally, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/pushpakrai/micro-blogging-sharegen.git
   cd micro-blogging-sharegen
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Set up environment variables:**
   - Duplicate `.env.example` and rename it to `.env`.
   - Update `.env` with your MongoDB URI, Clerk API keys, and other required credentials.

4. **Start the development server:**
   ```bash
   npm run dev
   ```

5. **Access ShareGen:**
   Open your browser and navigate to `http://localhost:3000` to view ShareGen locally.

## Usage

Once ShareGen is set up, you can:

- Create new posts and interact with existing content.
- Explore AI-generated responses and integrate them into your posts.
- Manage user profiles and engage with the community.

## Contributing

Contributions are welcome! To contribute to ShareGen:

1. Fork the repository on GitHub.
2. Create a new branch:
   ```bash
   git checkout -b feature/your-feature
   ```
3. Commit your changes:
   ```bash
   git commit -am 'Add new feature'
   ```
4. Push to the branch:
   ```bash
   git push origin feature/your-feature
   ```
5. Create a new Pull Request.

## License

This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for more details.
