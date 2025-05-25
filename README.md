# GenzAI

GenzAI is a full-stack MERN application that transforms text prompts into images using OpenAI's DALL-E API. Built with MongoDB, Express.js, React.js, Node.js, and styled with Tailwind CSS, it uses Cloudinary for image storage and features a community showcase for sharing creations.

## Table of Contents
- [Features](#features)
- [Technologies](#technologies)
- [Setup](#setup)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Features
- Generate images from text prompts using DALL-E.
- Share images to a community showcase with search functionality.
- "Surprise Me!" feature for random prompt-based image generation.
- Responsive UI with Tailwind CSS.
- Store and retrieve images via Cloudinary.
- Download or share generated images.

## Technologies
- **Frontend**: React.js, Tailwind CSS
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Image Storage**: Cloudinary
- **AI**: OpenAI DALL-E API
- **Tools**: JavaScript, Axios, MongoDB Atlas (optional)

## Setup


1. **Install Dependencies**:
   - Backend:
     ```bash
     cd server
     npm install
     ```
   - Frontend:
     ```bash
     cd ../client
     npm install
     ```

2. **Configure Environment Variables**:
   - Create a `.env` file in the `server` folder:
     ```
     MONGO_URI=your_mongodb_connection_string
     CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
     CLOUDINARY_API_KEY=your_cloudinary_api_key
     CLOUDINARY_API_SECRET=your_cloudinary_api_secret
     OPENAI_API_KEY=your_openai_api_key
     PORT=5000
     ```
   - Replace placeholders with your actual credentials.

3. **Run the Application**:
   - Backend:
     ```bash
     cd server
     npm start
     ```
   - Frontend:
     ```bash
     cd ../client
     npm start
     ```
   - Access at `http://localhost:3000` (frontend) and `http://localhost:5000` (backend).

## Usage
- **Generate Images**: Enter a text prompt or use "Surprise Me!" to create images via DALL-E.
- **Share**: Upload images to Cloudinary and share them to the community showcase.
- **Search**: Find images in the showcase by keywords or usernames.
- **Download**: Save images locally using the download button.

## Badges

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Node.js](https://img.shields.io/badge/Node.js-18.x-green)](https://nodejs.org/)
[![MongoDB](https://img.shields.io/badge/MongoDB-6.x-brightgreen)](https://www.mongodb.com/)
[![Express.js](https://img.shields.io/badge/Express.js-4.x-black)](https://expressjs.com/)
[![OpenAI](https://img.shields.io/badge/OpenAI-DALL--E-412991)](https://openai.com/)


## 📫 Let's Connect

[![LinkedIn](https://img.shields.io/badge/-LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/achyuth-kumar-698105325)
[![Twitter](https://img.shields.io/badge/-Twitter-1DA1F2?style=flat-square&logo=twitter&logoColor=white)](https://x.com/Achyuth88344725?t=aQNkQOXmCNs4581HVgKvzg&s=09)
[![Email](https://img.shields.io/badge/-Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:achyuthk865@gmail.com)
[![Instagram](https://img.shields.io/badge/-Instagram-E4405F?style=flat-square&logo=instagram&logoColor=white)](https://www.instagram.com/achyuth_kumar85/)

