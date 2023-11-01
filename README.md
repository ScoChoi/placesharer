# PlaceSharer


PlaceSharer is a web application that empowers users to share and discover intriguing places. This repository contains the source code for both the frontend and backend components of the PlaceSharer application.

## Deployed

https://placesharer-7cf31.web.app/

## Features

- **Place Discovery:** Explore a diverse range of interesting places shared by the community.
- **Place Sharing:** Contribute by sharing your favorite places along with detailed information.
- **User Authentication:** Securely log in and manage your profile.
- **Interactive Maps:** Visualize places on an interactive map.

## Getting Started

### Prerequisites

- Node.js: [Download and install Node.js](https://nodejs.org/)
- MongoDB: [Install MongoDB](https://docs.mongodb.com/manual/installation/)

### Installation

1. **Clone the repository:**

 ```bash
   git clone https://github.com/ScoChoi/placesharer.git
 ```

2. **Navigate to the `frontend` and `backend` directories:**
   
  ```bash
   cd placesharer/frontend
  ```
  ```bash
   cd placesharer/backend
  ```

3. **Install dependencies:**

  ```bash
   npm install
  ```

4. **Create a .env file in the backend directory and configure the following environment variables:**

  ```bash
   PORT=3000
   MONGODB_URI=mongodb://localhost:27017/placesharer
   JWT_SECRET=your_jwt_secret_key
  ```
   **Replace your_jwt_secret_key with a secure secret key for JWT authentication.**

5. **Run the application:**

```bash
npm start
```
**The frontend will be accessible at http://localhost:3000, and the backend server will be running at http://localhost:3000.**

## Usage
Describe how users can interact with the PlaceSharer application, including navigation, features, and any other relevant details.

## Documentation
For detailed information about the API endpoints and how to interact with them, refer to the API documentation.

## Contributing
If you would like to contribute to the development of PlaceSharer, please follow the guidelines in CONTRIBUTING.md.

## License
This project is licensed under the MIT License.

## Contact
For any inquiries, please contact the project owner:

- **Name:** Scott Choi
- **Email:** ascottychoi@gmail.com
- **GitHub:** https://github.com/ScoChoi
