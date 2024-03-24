# challenge-19-pwa

Week-19 Challenge (Progressive Web Applications)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Table of Contents

- [Description](#description)

- [Live-URL](#live-url)

- [Technologies-Used](#technologies-used)

- [Installation](#installation)

- [Features](#features)

- [Usage-Information](#usage-information)

- [Contribution-Guidelines](#contribution-guidelines)

- [Test-Instructions](#test-instructions)

- [License](#license)

- [Questions](#questions)

## Description

This application was specifically developed to showcase and enhance skills in progressive web application development. Its main goal was to gain a deeper understanding of the inner workings of the React JavaScript library. The application focuses on four key areas:
* 		Configuration: Setting up the webpack.config.js file with essential workbox plugins for service worker and manifest files, along with CSS and babel loader for compatibility with older code.
* 		Offline functionality: Implementing asset caching in the src-sw.js file to enable the application to work offline.
* 		Database integration: Configuring the database to facilitate data management, including addition, updating, and retrieval from the IndexedDB.
* 		User-friendly installation: Adding event handlers to the install button for easy installation on personal application stacks and offline usage.


## Live URL

https://challenge-19-pwa-c73358fe374a.herokuapp.com/

## Technologies Used

This application is powered by Webpack (HTML-Webpack-Plugin, Babel, and CSS Loader), Node.js (v16.19.1), Express.js (v.14.17.1), and JavaScript. Nodemon (v2.0.4) and Concurrently (v5.2.0) were utilized as a devDependencies allowing the server to refresh when edits were made to application, and allowing both the front end and back end to be ran on a single command (npm run start:dev).

![Webpack](https://img.shields.io/badge/webpack-%238DD6F9.svg?style=for-the-badge&logo=webpack&logoColor=black)
![Babel](https://img.shields.io/badge/Babel-F9DC3e?style=for-the-badge&logo=babel&logoColor=black)
![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![NPM](https://img.shields.io/badge/NPM-%23CB3837.svg?style=for-the-badge&logo=npm&logoColor=white)
![Nodemon](https://img.shields.io/badge/NODEMON-%23323330.svg?style=for-the-badge&logo=nodemon&logoColor=%BBDEAD)

## Installation

Users can view and utilize the application through the use of the browser by visiting the deployed application at https://challenge-19-pwa-c73358fe374a.herokuapp.com/.

Viewing the application in the browser will also give users the ability to download the application allowing it to be used offline.

To make any further additions, start by cloning the repo in the command line git clone https://github.com/johnlott1/challenge-19, or forking the repo.


## Features

Once the application is opened, the IndexedDB will persist any notes added to the site. There is no need to save any information as the application automatically updates the IndexedDB -> The only thing required for this feature to occur is that the user clicks out of the window. When returning to the site, they will find all of their notes and other information persisted to the page.

## Usage Information

Usage of this application is very intuitive, just visit the live URL (https://challenge-19-pwa-c73358fe374a.herokuapp.com/) and start adding notes right away! Users will also notice an install button in the nav bar allowing for the application to be downloaded and used offline. Saving of notes occurs automatically through the IndexedDB; the only thing required is for the user to click out of the window and notes will be persisted whether using the application online or offline.


## Contribution Guidelines

currently not accepting contributions at this time.

## Test Instructions

There is currently no unit testing written yet for this application.

## License

NOTICE: This application is covered under the MIT License

## Questions

Need more information? You can contact me through my Email. Link provided below.


Click to Email -> [Email](mailto:lott.john99@gmail.com?subject=[Email]%20Source%20Han%20Sans)