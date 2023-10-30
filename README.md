# Blood Bank MERN Stack Project

Blood Bank is a web application built using the MERN (MongoDB, Express, React, Node.js) stack. It serves as a platform for donors, organizations, hospitals, and administrators to manage and access blood-related information efficiently.

## Table of Contents

1. [Features](#features)
2. [Tech Stack](#tech-stack)
3. [Getting Started](#getting-started)
4. [Usage](#usage)
5. [Screenshots](#screenshots)
6. [Contributing](#contributing)
7. [License](#license)

## Features

- **Donor Module:**
  - User registration and login.
  - Donors can view the number of organizations they've donated to.
  - Donors can see a list of organizations available for donations.

- **Organization Module:**
  - User registration and login.
  - Display the inventory and availability of all eight blood groups.

- **Hospital Module:**
  - User registration and login.
  - View a list of organizations that have a particular blood type.
  - Access a list of consumers who have received a specific blood type.

- **Admin Module:**
  - User registration and login.
  - Administrative control over the Donor, Organization, and Hospital modules.

## Tech Stack

- Frontend:
  - React
  - Redux (for state management)
  - Axios (for making API requests)
  - React Router (for routing)
  
- Backend:
  - Node.js with Express (API development)
  - MongoDB (for data storage)
  
- Tools:
  - Postman (for testing API endpoints)
  - Visual Studio Code (for development)

## Getting Started

**1. Clone the repository:**
     ```bash
     git clone https://github.com/yourusername/Blood-Bank-Mern-Stack-Project.git
     cd Blood-Bank-Mern-Stack-Project
     
  ### Install dependencies
  
  1.1 For the frontend (inside the client directory):
  
      ```bash
      cd client
      npm install
  
  1.2 For the backend (in the project root):
  
      ```bash
      npm install

**2. Set up your environment variables:**

  Create a .env file in the project root to store environment variables like your MongoDB connection string, secret keys, and other sensitive data.

**3. Start the development servers:**

  3.1 For the frontend (inside the client directory):
    
    ```bash
    npm start

  3.2 For the backend (in the project root):

    ```bash
    npm run server
    
## Visit the Application

- Open your web browser and visit [http://localhost:3000](http://localhost:3000) to access the application.

## Usage

**Register and Log In:**
  - Register and log in to your respective module (Donor, Organization, Hospital, or Admin) to access the features and functionalities tailored to each user type.

**Explore Functionalities:**
  - Explore the various features provided for each module, including but not limited to:
    - Donor Module: Track donations, view available organizations.
    - Organization Module: Manage blood inventory.
    - Hospital Module: Access blood sources and consumer lists.
    - Admin Module: Administrative control over all other modules.

 **API Testing with Postman:**
  - If needed, you can use Postman to test and debug API endpoints. This can be particularly useful for troubleshooting and verifying the functionality of the backend API.

Feel free to use the application to its full extent, and don't hesitate to explore and make use of the various features and capabilities it offers.

## Screenshots

![New Website Blue Mockup Instagram - Laptop](https://github.com/HARSHUU-23/Blood-Bank-Management/assets/88359591/07c31cd8-2134-4619-ad41-2efd3695f794)


## Contributing

Contributions are welcome! If you'd like to contribute to this project, please follow these guidelines:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and test them thoroughly.
4. Commit your changes with clear and descriptive messages.
5. Push your branch to your forked repository.
6. Create a pull request to merge your changes into the main repository.

## License

This project is licensed under the MIT License.


