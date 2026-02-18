Basics of Node.js and npm / Yarn

Understanding Backend JavaScript Environment & Package Management

Presented by: Habtamua shambel Sarato

🟢 Slide 1: Introduction to Node.js
What is Node.js?
Node.js is:
✔An open-source JavaScript runtime
✔Built on Chrome’s V8 JavaScript Engine
✔Used to run JavaScript outside the browser
✔Mainly used for backend/server-side development

🟢 Slide 2: Why Node.js?
Key Features:

✔ Fast and efficient
✔ Non-blocking, asynchronous
✔ Event-driven architecture
✔ Scalable applications
✔ Large community support

Companies Using Node.js:
✔Netflix
✔PayPal
✔LinkedIn

🟢 Slide 3: How Node.js Works
Node.js uses:
✔Single-threaded event loop
✔Non-blocking I/O model
✔Asynchronous programming
   This makes it:
✔Lightweight
✔Fast
✔Perfect for real-time apps
    Examples:
✔Chat applications
✔APIs
✔Streaming apps

🟢 Slide 4: Installing Node.js
Steps:
1.Download from official website
2.Install LTS version
3.Verify installation
node -v
npm -v

If versions appear → Installation successful ✅

🟢 Slide 5: What is npm?
npm = Node Package Manager
npm is:
✔Default package manager for Node.js
✔Used to install libraries
✔Manages project dependencies
✔Runs scripts

🟢 Slide 6: What is Yarn?

Yarn is:
✔Alternative package manager
✔Developed by Facebook
✔Faster dependency installation
✔Uses yarn.lock file

🟢 Slide 7: npm vs Yarn Comparison
Feature	                                  npm                       	   Yarn
Install package	                          npm install	                    yarn add
Install all dependencies                  npm install                   	npm install	yarn
Lock file                              	  package-lock.json              	yarn.lock    
Speed                                   	Good	                          Sometimes faster

Both are used in modern development.

🟢 Slide 8: Creating a Node.js Project
Step 1: Create project folder
mkdir my-app
cd my-app
Step 2: Initialize project
npm init -y
This creates:
📄 package.json file

🟢 Slide 9: Understanding package.json
package.json contains:
✔Project name
✔Version
✔Dependencies
✔Scripts
✔Author information

Example script:
"scripts": {
  "start": "node index.js"
}

Run using:
✔npm start

🟢 Slide 10: Installing a Package

Example: Install Express
npm install express
or
yarn add express

Express.js is:
✔A fast and minimal Node.js web framework
✔Used to build APIs and servers

🟢 Slide 11: Simple Node.js Server Example
const http = require("http");
const server = http.createServer((req, res) => {
  res.write("Hello World");
  res.end();
});

server.listen(3000, () => {
  console.log("Server running on port 3000");
});

Run with:
node index.js
Open:
http://localhost:3000

🟢 Slide 12: Learning Outcome Achieved

After this study and practice, I can:

✅ Install Node.js
✅ Understand npm and Yarn
✅ Create and initialize a Node project
✅ Install and manage dependencies
✅ Create a basic server
✅ Run scripts using npm

🟢 Slide 13: Real-World Applications
Node.js is used for:
✔Backend APIs
✔Real-time chat apps
✔Authentication systems
✔Microservices
✔Full-stack development (React + Node)

🟢 Slide 14: Conclusion
Node.js allows JavaScript to run outside the browser.
npm and Yarn help manage packages and dependencies efficiently.
This knowledge builds the foundation for:

✔Backend development
✔Full-stack development
✔Modern web applications
