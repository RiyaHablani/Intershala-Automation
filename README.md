# Internshala Automation

## Overview

This project automates tasks on Internshala using Puppeteer, Node.js, and JavaScript. It simplifies resume building and internship applications by filling out details and applying for internships based on provided data.

## Features

- Logs into Internshala with provided credentials.
- Fills out resume details (graduation, training, work samples) using data from `data.js`.
- Applies for internships listed in a specific internship fair page.
- Submits applications with customized answers.

## How to Use

### Clone the Repository

Clone the repository:
git clone https://github.com/RiyaHablani/Oral_Cancer_Detection.git
cd Oral_Cancer_Detection

## Install Dependencies
Ensure Node.js and npm are installed. Install Puppeteer:
#### npm install puppeteer
### Setup Credentials and Data
Update secret.js:

- Replace id and pass variables with your Internshala login credentials.
Update data.js:

- Update this file with your resume details (e.g., college, degree, training, etc.).
Run the Script
Execute the main script using Node.js:

node script.js
### Notes
- Adjust timeouts (setTimeout) based on your network speed and system performance.
- Ensure all selectors (waitForSelector) match the latest version of Internshala's UI.
