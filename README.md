# Trivia Quiz

A basic trivia game build with Alpine.js.

## Local setup

1. Install [NodeJS and NPM](https://nodejs.org/en/) if you don't have them already.

1. Close this repository by running the following command:

   ```
   git clone https://github.com/n9iels/trivia-quiz.git
   ```

1. Navigate to the cloned repository and run the following command:

   ```
   npm install
   ```

   NPM will look the `package.json` file in the folder and install all dependencies.

1. Start the project using the following command:

   ```
   npm run serve
   ```

   A development server will start on <http://localhost:8080>.

## Making changes

The HTML of the quiz is located in `public/index.html`. Changes can be made directly in this file without additional step needed. The CSS of the quiz is located at `src/style.css`. This file can be edited, but in order to make the changes to the project you must run the command `npm run build`. This will generate the `public/css/style.min.css`. You can add `-- --watch` to the command to keep it running.

What IDE you use is entirely your decisions. If this IDE happends to be [Visual Studio Code](https://code.visualstudio.com/) a pop-up with extension recommendations will be shown after opening this project.
