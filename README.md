# razorpay-tailwind-clone
Cloned the Razorpay landing page using Tailwind CSS to practice responsive design and utility-first styling. This project replicates the layout and responsiveness of the original Razorpay site, showcasing modern UI techniques and clean frontend code.

✅ Deployed and hosted successfully
📁 Codebase pushed to GitHub


📦 Project Setup Instructions
To run this project locally, follow these steps carefully:          



🔧 Step 1: Install Node.js
Download and install Node.js (LTS version) from nodejs.org

Verify installation in your terminal:
node -v
npm -v

💡 If you face issues, check your system’s environment variables.



🧱 Step 2: Project Initialization & Tailwind Configuration

1.Create a new project folder and open it in VS Code.
2.Open terminal and run:
npm init -y

3.Install Vite:
npm i vite

4.Install Tailwind CSS and its dependencies:
npm install -D tailwindcss@3 postcss autoprefixer
npx tailwindcss init -p



🛠️ Step 3: Configuration Files

1.make a file postcss.config.js
module.exports = {
  plugins: {
    tailwindcss: {},
    autoprefixer: {},
  }
}

2.tailwind.config.js
/** @type {import('tailwindcss').Config} */
module.exports = {
  content: ["*"],
  theme: {
    extend: {},
  },
  plugins: [],
}

3.package.json
Update the scripts section:
"scripts": {
  "start": "vite"
}
Remove the default test script if it exists.



💅 Step 4: Styling & HTML
1.Create main.css and add:
@tailwind base;
@tailwind components;
@tailwind utilities;

2.Create index.html with:
<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link href="./main.css" rel="stylesheet">
</head>
<body>
  <h1 class="text-3xl font-bold underline">Hello world!</h1>
</body>
</html>



▶️ Step 5: Run the Project
Start the local server:
npm run start
You’ll receive a local development URL – open it in your browser to see your project live!

🛠️ Tech Stack
HTML5
Tailwind CSS
Vite
Node.js

📂 Folder Structure (Basic)
project-folder/
├── index.html
├── main.css
├── tailwind.config.js
├── postcss.config.js
├── package.json




                                      
