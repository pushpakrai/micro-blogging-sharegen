# ShareGen Microblogging Platform

ShareGen is a high-performance and scalable microblogging platform built with Next.js, Node.js, Gemini AI, and MongoDB. It empowers users with advanced AI-driven content creation features and robust authentication capabilities.

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

Welcome to ShareGen, a microblogging platform designed to enhance user engagement through dynamic content creation and seamless community interaction. This repository hosts the source code for ShareGen, allowing developers to explore, contribute, and customize the platform.

## Features

- **Dynamic Content Creation**: Create and share posts with AI-generated responses using Gemini AI.
- **Real-time Updates**: Utilize webhooks for instant notifications and real-time event handling.
- **User Authentication**: Secure authentication and profile management with Clerk, supporting email, password, and social logins.
- **Scalable Architecture**: Built on Next.js and Node.js, ensuring high performance and scalability.
- **Data Management**: MongoDB integration for handling complex data schemas and multiple data populations.
- **Responsive UI/UX**: Modern UI powered by Tailwind CSS for a responsive and visually appealing user experience.

## Tech Stack

- **Frontend**: Next.js, Tailwind CSS
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **AI Integration**: Gemini AI
- **Authentication**: Clerk
- **Other**: Webhooks, JavaScript (ES6+), TypeScript

## Installation

To run ShareGen locally, follow these steps:

1. **Clone the repository:**
   ```
   git clone https://github.com/pushpakrai/micro-blogging-sharegen.git
   cd micro-blogging-sharegen
   ```

2. **Install dependencies:**
   ```
   npm install
   ```

3. **Set up environment variables:**
   - Duplicate `.env.example` and rename it to `.env`.
   - Update `.env` with your MongoDB URI, Clerk API keys, and other necessary credentials.

4. **Start the development server:**
   ```
   npm run dev
   ```

5. **Access ShareGen:**
   Open your browser and navigate to `http://localhost:3000` to access ShareGen locally.

## Usage

Once ShareGen is set up locally, you can:

- Create new posts and interact with existing content.
- Explore AI-generated responses and integrate them into your posts.
- Manage user profiles and community interactions.

## Contributing

Contributions are welcome! To contribute to ShareGen:

1. Fork the repository on GitHub.
2. Create a new branch (`git checkout -b feature/your-feature`).
3. Commit your changes (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature/your-feature`).
5. Create a new Pull Request.

## Community

Join our active Discord community with over 27k+ members for support, feedback, and collaboration. Your input is valuable to us!

## License

This project is licensed under the MIT License - see the [LICENSE](./LICENSE) file for details.
