# Assignment 1---API-Automation-testing.
Execute Assignment Postman API collection using newman and generates report using htmlextra.
# clientSignUp
Welcome to the readme file for the Merchant Client Sign-Up application's Postman collection. This document will provide you with the necessary information to install and use the collection effectively.

## Installation
To install and set up the Merchant Client Sign-Up application's Postman collection, please follow the instructions below:

Ensure you have Node.js installed on your local machine. The application requires Node.js version 10 or higher. If you don't have Node.js installed, you can download it from the official Node.js website: https://nodejs.org

Make sure you have Npm (Node Package Manager) installed. The application requires Npm version 5 or higher. Npm usually comes bundled with Node.js, so if you have Node.js installed, you should also have Npm.

Install the newman command-line tool globally by executing the following command in your terminal:

```bash
$ npm install -g newman
```
Install the newman-reporter-htmlextra package globally by executing the following command in your terminal:

```bash
$ npm install -g newman-reporter-htmlextra
```
Download the Postman collection (VAI-\Assigment\.postman_collection.json) and the environment file (QA.postman_environment.json) from the provided source.

Open your terminal and navigate to the directory where you downloaded the files.

Run the following command in your terminal to execute the Postman collection and generate an HTML report:

```bash
$ newman run VAI-\Assigment\.postman_collection.json -e QA.postman_environment.json -r cli,htmlextra
```
This command will run the collection using the environment file and generate an HTML report using the newman-reporter-htmlextra reporter.

After the command finishes executing, you will find the generated HTML report in the output directory.

## Usage
To use the Merchant Client Sign-Up application's Postman collection, please follow the steps below:

Make sure you have completed the installation steps mentioned earlier.

Open Postman, a popular API development environment.

Import the Postman collection (VAI-\Assigment\.postman_collection.json) and the environment file (QA.postman_environment.json) into Postman.

Modify the environment variables in the imported environment file as per your specific setup. These variables may include API URLs, authentication tokens, or other configuration details.

Explore the available requests in the collection. Each request represents a specific functionality or API endpoint of the Merchant Client Sign-Up application.

Set the desired request parameters, such as headers, body, or query parameters, according to your testing requirements.

Execute the requests and observe the responses. Postman provides a rich set of features for testing APIs, including response validation, scripting, and debugging.

You can also execute the entire collection or specific request(s) using the collection runner in Postman. This allows you to automate the execution of multiple requests and perform tests at scale.

## Dependencies
To run the Merchant Client Sign-Up application's Postman collection successfully, make sure you have the following dependencies installed on your local machine:

Node.js >= 10: https://nodejs.org 

Npm > 5: Usually bundled with Node.js

newman: Install globally via npm install -g newman

newman-reporter-htmlextra: Install globally via npm install -g newman-reporter-htmlextra

Please ensure that you have these dependencies installed before executing the Postman collection.

Thank you for using the Merchant Client Sign-Up application's Postman collection. If you encounter any issues or have any questions, please feel free to reach out to our support team for assistance.

## Author

Kalyani Bhoite
