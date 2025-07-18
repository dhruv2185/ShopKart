# ShopKart

## Description
This is a Personalized Product Recommender system based E-commerce website. As the user interacts more and more with website by rating the products, they receive refined suggestions.

## Live Servers
- Frontend (Client) : https://shopkart-nu.vercel.app/
- Backend (Server) : https://shopkart-backend-pg6q.onrender.com/
- Recommender System (Colab) : http://b292-35-202-224-77.ngrok.io/

Note: Recommender System might crash due to large volume of training requests as it is hosted on a free server with limited resources, please contact one of the contributors to help you access the recommendation services.

## Table of Contents

- ### [Features](#features)
- ### [Installation](#installation)
- ### [Configuration](#configuration)
- ### [Usage](#usage)

## Features
- A Single Value Decomposition based Flask API
- Multi-threading based server to train the SVD model.
- Google OAuth 2.0
- Redux based cart features
- An attractive and easy to use user interface for a seamless experience.

 ## Installation
- Clone the project: `https://github.com/dhruv2185/shopkart.git`
- Navigate to the frontend directory: `cd frontend`
- Install the dependencies: `npm install`
- From the root directory, navigate to the backend directory: `cd backend`
- Install the dependencies: `npm install`
- Navigate to recommender folder: `cd recommender`
- Run the command: `python -m venv venv`
- For Linux, Activate the venv: `source ./venv/bin/activate`
- navigate to flask api folder: `cd flaskAPI`
- Run the command: `pip install -r requirements.txt`

## Configuration
- Replace the variables in `.env.example` in frontend.
- Replace the variable in `config/config.env` in backend

## Usage
- For frontend, run the command: `npm run dev`
- For backend, run the command: `npm run dev`
- For recommender, run the command: `python api.py`
