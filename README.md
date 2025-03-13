# personal-portfolio

## Welcome and thank you for checking out my personal portfolio showcasing my projects and skills

## Local Environment Setup

### Navigate to the folder where you store your projects:

cd path/to/your/projects

### Clone the GitHub respository to your local machine:

git clone https://github.com/yourusername/personal-portfolio.git
cd personal-portfolio

### Initialize a React project:

npx create-react-app

### Install dependencies:

npm install

### To check the current version of node and npm: (optional)

node -v
npm -v

### If you are not running the latest stable versions of node and npm:

npm install -g npm@latest

## Link project to GitHub:

git remote -v (the terminal should show your GitHub repo URL)

### Add all files to Git tracking:

git add .

### Commit the changes with a descriptive commit message:

git commit -m "Initial commit - Personal portfolio setup"

### Push the project to GitHub:

git push origin main

## Verify on GitHub:

Go to your repo
You should see the files uploaded

## Deploy to Netlify:

### Install Netlify CLI:

npm install -g netlify-cli

### Login to Netlify:

netlify login

### Deploy the project:

netlify deploy --prod (Netlify will generate a live URL - use this as your portfolio link)
