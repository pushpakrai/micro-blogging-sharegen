# ShareGen Microblogging Platform

**ShareGen** is an advanced microblogging platform engineered for performance and scalability. Built using cutting-edge technologies such as Next.js, Node.js, Gemini AI, and MongoDB, ShareGen is designed to enhance user engagement, streamline content creation, and provide real-time updates.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Welcome to **ShareGen**, a dynamic microblogging platform that leverages AI-driven content generation and fosters community engagement. This platform supports real-time interactions and offers flexible, scalable architecture. Explore the source code, contribute, and customize ShareGen to fit your project requirements.

## Features

- **AI-Driven Content**: Leverage Gemini AI to generate dynamic, responsive posts.
- **Real-time Event Handling**: Use webhooks to deliver real-time updates and notifications.
- **User Authentication**: Securely manage user credentials with Clerk, supporting multiple login options.
- **Scalable Architecture**: Built on Next.js and Node.js to ensure optimal performance.
- **Efficient Data Management**: Utilize MongoDB for handling complex data structures.
- **Modern UI/UX**: Tailwind CSS ensures a fully responsive, user-friendly interface.

## Tech Stack

- **Frontend**: Next.js, Tailwind CSS
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **AI Integration**: Gemini AI
- **Authentication**: Clerk
- **Additional Technologies**: Webhooks, JavaScript (ES6+), TypeScript

## Installation

Follow these steps to set up ShareGen locally:

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
   - Copy `.env.example` and rename it to `.env`.
   - Populate `.env` with your MongoDB URI, Clerk API keys, and any other required credentials.

4. **Start the development server:**
   ```bash
   npm run dev
   ```

5. **Access ShareGen:**
   Navigate to `http://localhost:3000` in your browser to access the platform.

## Usage

Once ShareGen is running, you can:

- Create and interact with posts.
- Leverage AI-generated responses via Gemini AI.
- Manage and update user profiles.
- Receive real-time notifications.

## Contributing

Contributions are welcome! Follow these steps to contribute:

1. Fork the repository on GitHub.
2. Create a new branch:
   ```bash
   git checkout -b feature/your-feature
   ```
3. Commit your changes:
   ```bash
   git commit -am 'Add new feature'
   ```
4. Push to your branch:
   ```bash
   git push origin feature/your-feature
   ```
5. Create a Pull Request on GitHub.

## License

This project is open-sourced under the MIT License. For more details, refer to the [LICENSE](./LICENSE) file.
