PlaceSharer
PlaceSharer Logo

PlaceSharer is a web application that enables users to share and discover interesting places. This repository contains both the frontend and backend code for the PlaceSharer application.

Table of Contents
Features
Getting Started
Prerequisites
Installation
Usage
Documentation
Contributing
License
Contact
Features
Place Discovery: Explore a variety of interesting places shared by the community.
Place Sharing: Contribute by sharing your favorite places with detailed information.
User Authentication: Securely log in and manage your profile.
Interactive Maps: Visualize places on an interactive map.
Getting Started
Prerequisites
Node.js: Download and install Node.js
MongoDB: Install MongoDB
Installation
Clone the repository:

bash
Copy code
git clone https://github.com/ScoChoi/placesharer.git
Navigate to the frontend and backend directories:

bash
Copy code
cd placesharer/frontend
bash
Copy code
cd placesharer/backend
Install dependencies:

bash
Copy code
npm install
Create a .env file in the backend directory and configure the following environment variables:

env
Copy code
PORT=3000
MONGODB_URI=mongodb://localhost:27017/placesharer
JWT_SECRET=your_jwt_secret_key
Replace your_jwt_secret_key with a secure secret key for JWT authentication.

Run the application:

bash
Copy code
npm start
The frontend will be accessible at http://localhost:3000, and the backend server will be running at http://localhost:3000.

Usage
Describe how users can interact with the PlaceSharer application, including navigation, features, and any other relevant details.

Documentation
For detailed information about the API endpoints and how to interact with them, refer to the API documentation.

Contributing
If you would like to contribute to the development of PlaceSharer, please follow the guidelines in CONTRIBUTING.md.

License
This project is licensed under the MIT License.

Contact
For any inquiries, please contact the project owner:

Name: Your Name
Email: your.email@example.com
GitHub: Your GitHub Profile
