# Vercel Clone

## Introduction

This project aims to replicate the core functionalities of Vercel, a popular platform for deploying and hosting frontend applications. With this clone, you can deploy and manage your applications with ease, leveraging the power of modern web technologies.

## Features

- **Deployments**: Easily deploy your applications with a simple drag-and-drop interface or through integration with GitHub repositories.
- **Custom Domains**: Manage custom domains and configure DNS settings effortlessly.
- **Serverless Functions**: Create and deploy serverless functions to handle backend logic and APIs.
- **Environment Variables**: Securely manage environment variables for your deployments.
- **Real-time Logs**: Monitor deployment logs and serverless function logs in real-time.
- **Automatic SSL**: Automatically provision SSL certificates for your custom domains.
- **Team Collaboration**: Invite team members and collaborate on projects with fine-grained access control.

## Tech Stack

- **Frontend**: React, Next.js, Tailwind CSS
- **Backend**: Node.js, Express.js, MongoDB
- **Real-time**: WebSockets
- **Deployment**: Docker, Kubernetes
- **CI/CD**: GitHub Actions

## Getting Started

### Prerequisites

- Node.js (v14.x or later)
- MongoDB (local or cloud instance)
- Docker (optional, for containerization)

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/saurabhdhingra/hostDost.git
   cd hostDost
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Set up environment variables:**
   Create a `.env` file in the root directory and add the following variables:
   ```plaintext
   MONGODB_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret_key
   ```

4. **Start the development server:**
   ```bash
   npm run dev
   ```

5. **Open your browser and navigate to:**
   ```
   http://localhost:3000
   ```

## Usage

### Deploying Applications

1. **Login or Sign Up:**
   Create an account or login with your existing credentials.

2. **Create a New Project:**
   Click on "New Project" and follow the instructions to connect your GitHub repository or upload your project files.

3. **Configure Build Settings:**
   Set the build and output settings for your project.

4. **Deploy:**
   Click "Deploy" to deploy your application. You can monitor the deployment status and logs in real-time.

### Managing Custom Domains

1. **Add a Domain:**
   Navigate to the "Domains" section and click "Add Domain".

2. **Configure DNS:**
   Follow the instructions to configure your DNS settings.

3. **Verify and Use:**
   Once verified, you can use your custom domain for your deployments.

### Creating Serverless Functions

1. **Create a New Function:**
   Navigate to the "Functions" section and click "New Function".

2. **Write Your Code:**
   Write your serverless function logic in the provided editor.

3. **Deploy:**
   Click "Deploy" to deploy your serverless function. You can monitor the function logs in real-time.

## Contributing

We welcome contributions to improve this project! To contribute:

1. **Fork the repository:**
   Click the "Fork" button on the top right corner of this repository page.

2. **Create a new branch:**
   ```bash
   git checkout -b your-feature-branch
   ```

3. **Make your changes and commit them:**
   ```bash
   git commit -m 'Add some feature'
   ```

4. **Push to the branch:**
   ```bash
   git push origin your-feature-branch
   ```

5. **Create a Pull Request:**
   Open a pull request on the original repository and describe your changes.


## Acknowledgments

- Inspired by the amazing work of Vercel.
- Thanks to the open-source community for their valuable contributions.
