##Internshala Automation
This project utilizes Puppeteer, Node.js, and JavaScript to automate tasks on Internshala, a popular internship platform. The automation helps in quickly building your resume and applying for internships based on the provided data.

##Project Overview
This automation script logs into Internshala using provided credentials, fills out details in the resume sections, saves work samples, and applies for internships. It significantly reduces the time required for these tasks.

##How to Use
To run the automation script on your machine, follow these steps:

Clone the Repository: git clone <https://github.com/RiyaHablani/Oral_Cancer_Detection.git>

##Install Dependencies:
Ensure Node.js and npm are installed. Then install Puppeteer:

npm install puppeteer
##Setup Credentials and Data:
Replace id and pass variables in secret.js with your Internshala login credentials.
Update data.js with your resume details (e.g., college, degree, training, etc.).

##Run the Script:
Execute the main script using Node.js:
node script.js

##Script Explanation
The main script (script.js) performs the following tasks:
Launches a headless browser (controlled by Puppeteer).
Logs into Internshala with provided credentials.
Fills out resume details (graduation, training, work samples) using data from data.js.
Applies for internships listed in a specific internship fair page.
Submits applications with customized answers.
