# Project Name: College Lost and Found(Findables.co)
![Alt Text](https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExb3JhNmNweW1hdXBxYnZvbndrMHNkbHY4MXFqemJremxlbjA0MzRxaiZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/wtHNn5w7DWyvB1Yh88/giphy.gif)

![Alt Text](https://drive.google.com/file/d/1ZxzNMCbsU_9q4fGndv8XeL1poJw9_wu3/view) 

## Project Inspiration
Colleges are often places where students frequently misplace their belongings, such as earphones, in various locations like desks, classrooms, or common areas. To address this common issue faced by college students, this project aims to create a user-friendly platform that allows users to report their lost or found items. By providing a centralized system, it becomes easier for students to recover their lost belongings and make sure they are returned to the rightful owners.

## Features
- **Real-time Notifications:** Users will receive instant notifications when someone lists a lost or found item that matches their description.
- **Response Validation:** To ensure the accuracy and prevent false claims or misuse of information, a "Response Validation" technique is implemented. This feature adds an extra layer of security and reliability to the system.
- **Item and Response Tracking:** Users can easily keep track of the items they have listed as lost or found and monitor responses from other users.
- **User-Friendly Interface:** The platform provides a simple and intuitive user interface, making it easy for anyone to use and navigate without any hassle.

## Technologies Used
Findables.co is built using the MERN (MongoDB, Express.js, React, Node.js) stack, providing a robust and scalable foundation for the application. The technologies used in the project include:

- Front-end:
  - React: A JavaScript library for building user interfaces.
  - Redux: For state management in the React application.
  - HTML5 and CSS3: For creating the layout and styling of the user interface.
  - Axios: A promise-based HTTP client for handling API requests.

- Back-end:
  - Node.js: A JavaScript runtime for server-side development.
  - Express.js: A web application framework for Node.js.
  - MongoDB: A NoSQL database for storing findables and user information.
  - Mongoose: An Object Data Modeling (ODM) library for MongoDB and Node.js.

- Authentication:
  - JSON Web Tokens (JWT): For secure user authentication and authorization.

## Getting Started
To run the Findables.co project locally on your machine, follow these steps:

1. Clone the repository from GitHub:

   ```
   git clone https://github.com/chayan/findables.co.git
   ```

2. Install the required dependencies for both the front-end and back-end:

   ```
   cd findables.co/frontend
   npm install
   cd ../backend
   npm install 
   node server.js
   ```

3. Set up environment variables:
   - Create a `.env` file in the `/server` directory and define the following variables:
     - `MONGODB_URI`: Connection string for your MongoDB database.
     - `JWT_SECRET`: A secret key used for signing and verifying JSON Web Tokens.
     - `PORT`: Port number for the server to run (e.g., 5000).

4. Populate the MongoDB database with initial data if needed (e.g., predefined categories, sample findables).

5. Access the application in your web browser at `http://localhost:3000` (assuming the front-end runs on port 3000).

## Project Hosting
The project is hosted at: [https://findables-frontend.vercel.app/](https://findables-frontend.vercel.app/)

## Figma Design
Explore the Figma design for the project [here](https://www.figma.com/proto/gmrXlNN474p5OO9zgZZpiw/Untitled?type=design&node-id=1-4&t=imaAQ5cBIKm0eZKK-1&scaling=scale-down&page-id=0%3A1&starting-point-node-id=1%3A4&show-proto-sidebar=1&mode=design).


## Contribution
If you find any bugs or want to contribute to the project, feel free to open an issue or submit a pull request. We welcome contributions from the community to make this project even better!


## Contact
If you have any questions or need further assistance, you can reach out to the project maintainers at [manikchadha0609@gmail.com](mailto:manikchadha0609@gmail.com).
