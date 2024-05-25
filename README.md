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
