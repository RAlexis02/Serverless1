# Serverless1


Serverless1 Project - Simple Addition Web Application
This project, Serverless1, is a basic static web application that demonstrates the addition of two numbers. The application is deployed on Railway, allowing easy and free hosting for simple projects.

📋 Project Overview
Serverless1 is a simple web application where users can input two numbers and get the sum as output. It’s designed to demonstrate a basic HTML and JavaScript interface. The application is suitable for beginner-level projects and is easily deployable on serverless platforms like Railway.

🛠 Requirements
To deploy this project on Railway, you’ll need:

A GitHub account where your project is stored.
A Railway account. Sign up at Railway.app.
The project files, specifically index.html (and any necessary JavaScript or CSS files).
📂 Project Structure
plaintext
Copiar código
Serverless1/
├── index.html       # Main HTML file for the web interface
└── README.md        # Documentation file explaining the project and deployment
index.html: Contains the HTML and JavaScript code for the addition functionality.
README.md: Provides a guide on how to set up and deploy the project on Railway.
🚀 Step-by-Step Deployment on Railway
Follow these steps to deploy the Serverless1 project on Railway.

Step 1: Set Up the Project in GitHub
Create a GitHub Repository: If you haven’t already, create a repository on GitHub for Serverless1.
Upload Project Files: Ensure that index.html and any associated files (e.g., JavaScript files) are in the repository’s root directory.
Commit Changes: Once all files are added, commit and push the changes to the main branch on GitHub.
Step 2: Set Up a Railway Account and Connect GitHub
Sign Up/In to Railway: Go to Railway.app and sign in or create an account.
Connect GitHub: In Railway’s dashboard, go to settings and link your GitHub account. This will allow Railway to access your repositories for deployment.
Step 3: Deploy the Project on Railway
Create a New Project:

On the Railway dashboard, click on New Project.
Select Deploy from GitHub repo to deploy from an existing GitHub repository.
Select the Repository:

Choose the Serverless1 repository from the list.
Railway will automatically detect that it is a static project and set up the environment.
Configure Settings:

Root Directory: In the Settings tab of Railway, set the Root Directory to / if it isn’t set automatically. This ensures Railway serves the files from the root folder.
Generate a Public Domain:

Go to the Settings tab in Railway and scroll to Networking.
Under Public Networking, click Generate Domain. Enter 8080 as the target port if prompted.
Railway will create a public URL for your application, such as https://serverless1-production.up.railway.app.
Step 4: Access the Application
Open the Generated URL:

Copy the URL provided by Railway (e.g., https://serverless1-production.up.railway.app).
Open it in a browser to test and use the application.
Verify the Functionality:

Input two numbers in the provided fields on the webpage.
Click the "Add" button to display the result.
🔄 Summary of Commands for GitHub
For quick reference, here are the basic Git commands to upload your project to GitHub.

bash
Copiar código
# Initialize a new Git repository (if needed)
git init

# Add all project files
git add .

# Commit the changes
git commit -m "Initial commit of Serverless1 project"

# Push to GitHub (replace 'main' if your branch name is different)
git push origin main
💡 Troubleshooting Tips
If you encounter issues while deploying, here are some things to check:

Root Directory: Ensure the index.html is in the root directory of your repository.
Public Networking: Verify that you generated a domain under Public Networking in Railway’s Settings.
Port Settings: If prompted, use port 8080 to expose the service.
📜 License
This project is open-source and available under the MIT License.