# Social-Network-API

Week-18 Challenge (MongoDB)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) [![Contributor Covenant](https://img.shields.io/badge/Contributor%20Covenant-2.1-4baaaa.svg)](code_of_conduct.md)

## Table of Contents

- [Description](#description)

- [Live-Screen-Recording-of-Application-Functionality](#live-screen-recording-of-application-functionality)

- [Technologies-Used](#technologies-used)

- [Installation](#installation)

- [Features](#features)

- [Usage-Information](#usage-information)

- [Suggested-Future-Development](#suggested-future-development)

- [Contribution-Guidelines](#contribution-guidelines)

- [License](#license)

- [Questions](#questions)

## Description

This application marks the inception of a comprehensive full-stack social networking platform, employing MongoDB for data storage, Express.js for routing, and the Mongoose ODM for interaction. It establishes the foundational CRUD API routes, empowering users to create, search, update, and delete their profiles. Users can also share thoughts, react to their friends' thoughts, manage their friend lists, and subsequently remove thoughts, reactions, friends, and their own profiles. While this application is still in its nascent stage, the MongoDB database and API middleware routing serve as crucial initial steps in exploring the potential of MongoDB and the Mongoose ODM.

During the development process, I encountered several challenges. Despite MongoDB's flexibility in data querying and addition compared to SQL, I found that error tracking was more elusive, making troubleshooting more challenging. Additionally, optimizing data deletion on cascade and managing joins presented difficulties. MongoDB's simplicity in code compared to SQL came with a learning curve due to the underlying complexity that I'm still working to grasp fully.

Notwithstanding these challenges, this project has expanded my toolkit in the MERN stack, enriching my understanding of full-stack development. Moving forward, I intend to further develop this application by incorporating a full-fledged front-end UI with React, thereby transforming it into a complete MERN-based full-stack application.

## Live Screen Recording of Application Functionality 

https://drive.google.com/file/d/1MQ2WUP7RbTJPUuadVkVzzmjbWWJe8IWU/view

## Technologies Used

This application leverages Node.js (v16.19.1), Express.js (v.14.18.2), JavaScript, MongoDB, and Mongoose (ODM). It employs npm dependencies such as express (v4.18.2) and mongoose (v7.2.2). Nodemon (v2.0.22) is used as a devDependency to automatically restart the server upon any changes to the application. Jest (v.29.5.0) is also included as a devDependency for potential unit testing in the future. MongoDB Compass serves as the graphical interface for visualizing the database, while the Insomnia application is used for testing the route functionality within the program.

![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB)
![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![NPM](https://img.shields.io/badge/NPM-%23CB3837.svg?style=for-the-badge&logo=npm&logoColor=white)
![Nodemon](https://img.shields.io/badge/NODEMON-%23323330.svg?style=for-the-badge&logo=nodemon&logoColor=%BBDEAD)
![Jest](https://img.shields.io/badge/-jest-%23C21325?style=for-the-badge&logo=jest&logoColor=white)
![Insomnia](https://img.shields.io/badge/Insomnia-black?style=for-the-badge&logo=insomnia&logoColor=5849BE)

## Installation Steps

Follow these steps to set up and run the application:

1. Clone the repository:
   ```
   git clone https://github.com/Donsidious/Social-Network-API
   ```

2. Open the project in Visual Studio Code. If you don't have VS Code installed, please install it.

3. Install Node.js version 16. If you have Homebrew, you can use the following command to install it:
   ```
   brew install node@16
   ```
   Note: The installation method may vary, so consult the documentation if needed.

4. Once Node.js version 16 is installed, initialize a `package.json` file by running the following command in the terminal:
   ```
   npm init -y
   ```

5. Install the dependencies associated with this application using the following commands in the terminal:
   - To install Express, run:
     ```
     npm i express@4.18.2
     ```
   - To install Mongoose, run:
     ```
     npm i mongoose
     ```
   - To install Nodemon, run:
     ```
     npm i nodemon
     ```
   - To install Jest, run:
     ```
     npm i jest
     ```

6. Ensure that you have access to a MongoDB account and have MongoDB Compass installed. These tools will allow you to interact with the database and visualize database changes. You can download MongoDB and MongoDB Compass from this link: [MongoDB & MongoDB Compass Download](https://coding-boot-camp.github.io/full-stack/mongodb/how-to-install-mongodb).

7. Once all dependencies are installed, you can start the server by running the following command from the root directory:
   ```
   npm start
   ```
   If you have Nodemon installed, you can use the following command to keep the server running during code edits:
   ```
   npm run dev
   ```

8. After starting the server, you can use tools like Insomnia to test the functionality of the API routes within the application. You can install Insomnia from this link: [Insomnia Installation](https://docs.insomnia.rest/insomnia/install).

## Features

This application offers a range of features, including user and thought creation, retrieval of all users and thoughts, fetching a single user or thought, updating user and thought information, and deleting users and thoughts. Additionally, it allows users to add reactions to specific thoughts and establish friendships with other users. Notably, any additions to the database, whether it be a thought, reaction, or friend, will automatically update within the corresponding user object.

## Usage-Information

To utilize this application, you can start the server by running either `npm run start` or `npm run dev` with nodemon. Afterward, you can test various API endpoints using tools like Insomnia or Postman. For more detailed instructions on setting up the server, MongoDB Compass, and MongoDB installation, please refer to the Installation section above.

## Suggested Future Development

-Enrich the seed data by incorporating the faker-js package from node package manager

-Extend the application's functionality by developing additional routes for likes or up-votes

-Develop a user-friendly front-end UI to facilitate seamless interaction with the application

-Incorporate Jest for unit testing to ensure code reliability and performance

## Contribution Guidelines

If you're interested in collaborating, please open an issue and make your proposed changes on a feature branch. Wait for approval before merging your changes into the main branch.

Please note: The Contributor Covenant is licensed under the Creative Commons Attribution 4.0 International Public License. This license requires the inclusion of attribution

## License

NOTICE: This application is covered under the MIT License

## Questions

[Link to Github](https://github.com/Donsidious/Social-Network-API)

