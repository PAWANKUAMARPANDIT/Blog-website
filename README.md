# Blog Application

## Overview

Welcome to the Blog Application! This application allows users to create, update, and view blog posts. It includes user authentication, post management, and more, built with Appwrite for the backend and Vite for the frontend. The application also utilizes React and Redux for state management.

## Table of Contents

- [Features](#features)
- [Technologies](#technologies)
- [Getting Started](#getting-started)
- [Setup Instructions](#setup-instructions)
- [Usage](#usage)
- [Contributing](#contributing)

## Features

- User authentication (sign up, login, logout)
- Create, update, and delete blog posts
- View all blog posts
- User-friendly interface with responsive design
- State management with Redux

## Technologies

- **Frontend:** React, Vite, React-Redux
- **Backend:** Appwrite
- **Styling:** Tailwind CSS 
- **Database:** Appwrite's Database service

## Getting Started

### Prerequisites

- Node.js (v14 or later)
- Appwrite server instance running locally or on a cloud provider
- Basic knowledge of React and Redux

### Setup Instructions

1. **Clone the Repository**

   ```bash
   git clone https://github.com/PAWANKUAMARPANDIT/Blog-website.git
   cd blog
   ```
2. Install Dependencies

   For the frontend:
  ```bash
  npm install
  ```
For the backend, refer to the Appwrite documentation to set up your project and install any necessary SDKs.

3. Configure Appwrite

Get the APPWRITE_URL from Appwrite to add in envfile

Create a new project in your Appwrite console.

Set up your database with collections for users and blog posts.

Obtain your Appwrite endpoint to get project ID,database Id,and collection Id,bucket Id.

4. Environment Variables

Create a .env file in the frontend directory with the following variables(for vite it's like that)

```bash
VITE_APPWRITE_URL="https://cloud.appwrite.io/v1"
VITE_APPWRITE_PROJECT_ID=""
VITE_APPWRITE_DATABASE_ID=""
VITE_APPWRITE_COLLECTION_ID=""
VITE_APPWRITE_BUCKET_ID=""
```

5. Start the Development Server

To run the server run the command:
```bash
npm run dev
```

Your application should now be running at http://localhost:5173.

### Usage

- **User Authentication**:
- Users can sign up or log in to access the blog features.
- **Managing Posts**:
- Authenticated users can create new posts, edit existing ones, and delete posts they own.
- Users can view all posts on the main page.

### Contributing
Contributions are welcome! If you'd like to contribute to the project, please follow these steps:

1. Fork the repository.
2. Create a new branch 
```bash  
git checkout -b feature/YourFeature 
```
3. Make your changes and commit them 
```bash 
git commit -m 'Add some feature' 
```
4. Push to the branch 
```bash
git push origin feature/YourFeature
```
Open a pull request to contribute to this project.

  
