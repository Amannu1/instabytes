# Instabytes

![Google Gemini](https://img.shields.io/badge/google%20gemini-8E75B2?style=for-the-badge&logo=google%20gemini&logoColor=white)
![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB)
![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white)

This project is a back-end application for a photo-sharing social network, built using **Node.js** and **MongoDB**.

The application exposes a REST API responsible for managing posts, handling image uploads, implementing a like system, and integrating with generative AI to automatically create photo descriptions.

The API simulates the core functionality of a modern social media platform, where users can create and interact with posts, upload images, and receive AI-generated captions to enhance their content.

## Table of Contents

- [Technologies](#technologies)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [License](#license)

## Technologies

- NodeJS
- Google Gemini API
- MongoDB
- Mongoose
- Express

## Prerequisites

- [NodeJS](https://nodejs.org/en)
- [MongoDB](https://www.mongodb.com/)

## Installation

1. Clone the repository:

```bash
git clone https://github.com/Amannu1/instabytes
```

2. Access project directory:
```bash
cd instabytes
```

3. Install node dependencies:
```bash
npm install
```

4. Configure environment settings:

    Create a .env with the content below:
    
    STRING_CONEXAO="mongodb+srv://usuario:senha@cluster.mongodb.net/database-name"
    GEMINI_API_KEY="your_gemini_api_key"
    
    STRING_CONEXAO: MongoDB connection string
    GEMINI_API_KEY: Google Gemini API

5. Start the application:
```bash
npm run dev
```

## License

MIT



