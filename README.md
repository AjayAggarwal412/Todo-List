# Todo-List

Steps and installation

1. Download the zip file and store it in a desired location.
2. Open command prompt and locate to the location where you have unzipped the "ToDolistMain" folder.

   Example

   ```
   cd desktop/
   C:\Users\HP\desktop> cd ToDolistMain
   C:\Users\HP\desktop\ToDolistMain>
   ```

3. Now install some packages using below commands:

   ```
   npm install
   ```

   This will install npm module in the project.

   ```
   npm install express
   ```

   This will install express module in the project.

   ```
   npm install body-parser
   ```

   This will install body-parser module in the project.

   ```
   npm install ejs
   ```

   This will install ejs module in the project.

   ```
   npm i -g npm
   ```

   ```
   npm i --save lodash
   ```

   This will install Lodash library in the project.

4. Now in the text editor(Visual Studio Code),Open package.json file and check all the dependencies which we have installed.

   For example:

   ```json
   {
      "name": "ejs-challenge",
      "version": "1.0.0",
      "description": "",
      "main": "app.js",
      "scripts": {
      "test": "echo \"Error: no test specified\" && exit 1"
   },
   {
      "author": "",
      "license": "ISC",
      "dependencies": {
      "body-parser": "^1.18.3",
      "ejs": "^2.6.1",
      "express": "^4.16.3",
      "lodash": "^4.17.20"
   }
   ```

5. Now open your web browser and type: "localhost:3000".This will run your project.
