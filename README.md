# AI-Powered-Recipe-Finder

## Overview

This AI-Powered Recipe Finder is a web app that aims to identify ingredients in the user's fridge from an uploaded image and suggests personalized recipes based on those ingredients. This app leverages image recognition and machine learning to enhance the user experience in meal planning and cooking.

## Features

- **User Authentication**: Secure registration and login.
- **Image Upload**: Upload pictures of your fridge to identify ingredients.
- **Image Recognition**: AI-based identification of ingredients using TensorFlow and OpenCV.
- **Recipe Suggestions**: Personalized recipes fetched from the Spoonacular API.
- **Ingredient Management**: Add or remove ingredients manually.
- **Recipe Filtering**: Filter recipes based on dietary preferences or restrictions.
- **User Preferences**: Save and manage user preferences and recipe history.

## Tech Stack

### Frontend
- **React**: JavaScript library for building user interfaces.
- **Redux**: State management for React applications.
- **Chart.js/D3.js**: For data visualization.

### Backend
- **Node.js**: JavaScript runtime for building server-side applications.
- **Express**: Web framework for Node.js.
- **MongoDB**: NoSQL database for storing user data, images, ingredients, and recipes.
- **JWT**: JSON Web Tokens for secure user authentication.

### Image Recognition and AI
- **TensorFlow**: Open-source library for machine learning and artificial intelligence.
- **OpenCV**: Open-source library for computer vision and image processing.
- **Generative AI (GenAI)**: To generate additional recipes or variations.
- **Large Language Model (LLM)**: To enhance recipe recommendations and user interactions.

### APIs
- **Spoonacular API**: For fetching recipes based on recognized ingredients.

### Deployment
- **Primary Deployment Platform**: AWS (Amazon Web Services)
- **Alternative Deployment Platforms**: GCP (Google Cloud Platform), Azure (Microsoft Azure)

### CI/CD
- Set up Continuous Integration and Continuous Deployment pipelines for automated testing and deployment.

