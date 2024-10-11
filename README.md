# React + Vite
This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

To set up follow the steps:

Step 1: Clone the Repository
git clone <repository_url> cd <repository_folder_name>

Step 2: Create a Vite React App
npm create vite@latest my-first-react-app -- --template react

Step 3: Move the Created App to the Current Directory Using rsync
rsync -av --progress my-first-react-app/ . --exclude my-first-react-app

Step 4: Remove the Empty Directory
rm -rf my-first-react-app

Step 5: Install Dependencies
npm install

Step 6: Start the Development Server
npm run dev

///////// Personal notes: Test uuidv4 on other projects; how to improve paragraph logic and text lines in description, make look better

-  -  -  -  -  -  -  -  -  -  -  -  -  -  -  -  -  -  -  -  -  -  

# template-repo-odin

This is just a template repository for Odin projects

Prerequisites
You will need Node.js and npm installed globally on your machine.

Install NPM packages

    npm install

Build an app

    npm run build (after each command src JS's goes to dist main.JS)

Quick tip: If you run npx webpack --watch you will not have to rerun webpack every time you make a change.

Usage

    Open ./dist/index.html file with browser.

To host page thru GitHub:
Step 1
Make sure git knows about your subtree (the subfolder with your site).

    git add dist && git commit -m "Initial dist subtree commit"

Step 3
Use subtree push to send it to the gh-pages branch on GitHub.

    git subtree push --prefix dist origin gh-pages

Boom. If your folder isn’t called dist, then you’ll need to change that in each of the commands above.

**_ If you do this on a regular basis, you could also create a script somewhere in your path, just visit Odin's Project: Restaurant Page and read instuctions _**
