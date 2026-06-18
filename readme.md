# Backend Folder Creation Steps
- Step 1: Create a New Folder

- Step 2: ` npm init -y `
(package.js)

- Step 3: Rename the index.js into main.js in package.json

- Step 4: Create a **main.js** file

- Step 5: Dependency Installation
` npm i express `
(node_modules)

- Step 6: Create a **.gitignore** file and add the node_modules folder name into it

- Step 7: Create a complete Express Server (refer to the main.js file)

- Step 8: Install the nodemon library using this below command
` npm i -D nodemon `

- Step 9: Add a **dev** script in package.json file
` "scripts": { `
   ` "dev": "nodemon main.js", `
` } `

- Step 10: For starting the application
` npm run dev `

--------------------------------------------


nodemon (old) 
2026 trend -> alternate:

alter -> package.json
"scripts": {
  "start": "node main.js",
  "dev": "node --watch main.js"
}
// command terminal "ctrl + c" server stop
 after type and enter "npm start"
