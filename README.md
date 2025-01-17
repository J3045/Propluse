Propluse

Propluse is a dynamic freelancing marketplace website designed to connect freelancers with clients looking for various services. This application is developed using the MERN stack (MongoDB, Express.js, React, Node.js) and includes features such as user authentication, project management, and payment processing with Stripe.

Table of Contents

Features
Technologies Used
Installation
Usage
Environment Variables
Contributing
License
Contact

Features

User authentication and authorization
Freelancer and client profiles
Project posting and bidding
Secure payment processing with Stripe
Real-time notifications
Responsive design for mobile and desktop

Technologies Used

Frontend: React, Redux, Bootstrap
Backend: Node.js, Express.js
Database: MongoDB, Mongoose
Payment Processing: Stripe
Hosting: Vercel/Netlify (Frontend), Render (Backend)

Installation

Prerequisites
Node.js
MongoDB

Backend
Clone the repository:

sh
Copy code
git clone https://github.com/J3045/Propluse.git
cd Propluse/backend
Install dependencies:

sh
Copy code
npm install
Create a .env file in the backend directory and add the following variables (refer to the .env.sample file):

env
Copy code
MONGO_URI=your_mongo_uri
STRIPE_SECRET_KEY=your_stripe_secret_key
JWT_SECRET=your_jwt_secret
Start the backend server:

sh
Copy code
npm start
Frontend
Navigate to the frontend directory:

sh
Copy code
cd ../frontend
Install dependencies:

sh
Copy code
npm install
Create a .env file in the frontend directory and add the following variables (refer to the .env.sample file):

env
Copy code
REACT_APP_API_URL=your_backend_api_url
REACT_APP_STRIPE_PUBLIC_KEY=your_stripe_public_key
Start the frontend development server:

sh
Copy code
npm start
Usage
Open your browser and navigate to http://localhost:3000 for the frontend.
The backend server runs on http://localhost:5000 by default.
Environment Variables
Ensure you set up the following environment variables:

Backend .env file:
env
Copy code
MONGO_URI=your_mongo_uri
STRIPE_SECRET_KEY=your_stripe_secret_key
JWT_SECRET=your_jwt_secret
Frontend .env file:
env
Copy code
REACT_APP_API_URL=your_backend_api_url
REACT_APP_STRIPE_PUBLIC_KEY=your_stripe_public_key
Contributing
Contributions are welcome! Please follow these steps:

Fork the repository.
Create a new branch: git checkout -b feature-name.
Make your changes and commit them: git commit -m 'Add some feature'.
Push to the branch: git push origin feature-name.
Open a pull request.
License
This project is licensed under the MIT License.

Contact
Jainikkumar Patel - jainikpatel824@gmail.com

Project Link: https://github.com/J3045/Propluse
 
