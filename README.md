# StudyNotion EdTech Project

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Technologies Used](#technologies-used)
- [Folder Structure](#folder-structure)
- [Contributing](#contributing)
- [License](#license)

## Introduction
**StudyNotion** is a modern EdTech platform aimed at revolutionizing the way students access and engage with educational content. It offers a user-friendly interface and a feature-rich environment that enhances learning through interactive courses, quizzes, and multimedia content. Whether you're an educator or a student, StudyNotion provides tools to make education accessible, engaging, and effective.

## Features
- **Course Creation and Management**: Easily create and manage educational courses with a variety of media types including videos, PDFs, and interactive content.
- **User Authentication**: Secure user login, signup, and profile management.
- **Responsive Design**: Optimized for mobile, tablet, and desktop devices.
- **Quiz & Assessment**: Integrated quizzes to help users evaluate their learning.
- **Community Interaction**: Discussion boards for students and instructors to engage with each other.
- **Admin Dashboard**: Comprehensive control over users, content, and platform performance.

## Installation
Follow the steps below to set up the project on your local machine.

1. **Clone the Repository:**
   `git clone https://github.com/VishalPSIT/Study-notion.git`  
   `cd studynotion-edtech-project`

2. **Install Dependencies:**
   Make sure you have [Node.js](https://nodejs.org/) installed. Then, run the following command:  
   `npm install`

3. **Set Up Environment Variables:**
   Create a `.env` file in the root directory and configure the necessary environment variables:
   - `PORT=5000`
   - `DATABASE_URL=<your-database-url>`
   - `JWT_SECRET=<your-jwt-secret>`

4. **Start the Development Server:**
   To start the local server, run:  
   `npm run dev`  
   The application will be available at `http://localhost:5000`.

## Usage
Once the project is installed and running, you can access the platform through your web browser. Here are some things you can do:
- Create a new course as an instructor.
- Enroll in courses as a student.
- Participate in discussions and take quizzes.

## Technologies Used
- **Frontend**: React, Tailwind CSS
- **Backend**: Node.js, Express
- **Database**: MongoDB
- **Authentication**: JWT (JSON Web Tokens)
- **Version Control**: Git
- **Other Tools**: Prettier, ESLint

## Folder Structure
Study-notion/
├── public/                 # Static files
├── server/                 # Backend logic
├── src/                    # Frontend source code
├── package.json            # Project metadata and dependencies
├── tailwind.config.js      # Tailwind CSS configuration
├── .gitignore              # Git ignore file
└── README.md               # Project documentation (this file)

## Contributing
We welcome contributions from the community! To contribute:
1. Fork the repository.
2. Create a new branch: `git checkout -b feature-name`.
3. Make your changes and commit: `git commit -m 'Add some feature'`.
4. Push to the branch: `git push origin feature-name`.
5. Submit a pull request.
