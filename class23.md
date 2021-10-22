# ✍️ Notes

1. What does CLI stand for?
    - Command Line Interface
    - Command Line Interpreter
    - Command Line Input
    - AKA Linux Terminal

2. What is the command line used for?
    - CLI is used by software developers and system administrators to configure computers, install software, and access features that are not available in the graphical interface.

3. What is the command that creates a new React app?
    - npx create-react-app name-my-app

4. What does create-react-app do?
  - Create React App is a comfortable environment for learning React, and is the best way to start building a new single-page application in React. It sets up your development environment so that you can use the latest JavaScript features, provides a nice developer experience, and optimizes your app for production. When we use create-react-app tool it creates a hierarchy of files and folder in an out-of-the-box, working application for us.

5. What does npx stand for?
    - Node Package Executer

6. What does npx do?
    - NPX comes built into npm. It is a node package runner and can execute any package/directory/library from the npm registry(the internet) without installing the package globally on your computer.

7. What does npm stand for?
    - Node Package Manager

8. What does npm do?
    - npm is the dependency/package manager you get out of the box when you install Node.js. It is a command line tool that aids you in installing packages both globally and locally; and manages their versions and dependencies.

9. What are the differences between npm and npx?
    - NPM is a tool that is used to install packages and NPX is a tool that is used to execute packages.

10. What is the command that starts the React server?
    - npm start

11. What URL do I navigate to in order to view my React app in the browser?
    - http://localhost:3000 (unless you already have something running on that port)

12. What is the purpose of a package.json?
    - It recors important metadata about a project which is required before publishing to NPM. It also defines functional attributes of a project that npm uses to install dependencies, run scripts, and indentify the entry point to our package. It specifies the dependencies being used in the project which helps npm setup the same environment on a different machine for our project.

13. What are node modules?
    - The node_modules folder is used to save all downloaded packages from NPM in your computer for the JS project that you have

14. What is the .gitignore?
    - This file specifies intentionally untracked files that Git should ignore. Any files liseted in the .gitignore will NOT be pushed up to GitHub. This is useful to kep things like your secret keys safe, or to prevent pushing dependencies, like node_module, to GitHub.

15. What is the purpose of the public directory?
    - This golder contains the HTML file, index.html. This is the page template and must named exactly this because it is the template file which is served up when we start our script to launch our app. It is considered best practive not to create multiple html files in the public folder. You would normally only work in this folder when importing css

16. What is the purpose of the public/index.html?
    - your answer goes here...

17. What is the purpose of the src directory?
    - In simplest form it's the mind of our app

18. What is the purpose of the src/index.js?
    - your answer goes here...

19. What is significant about this line of code?
`ReactDOM.render(<App />, document.getElementById(‘root’));`
    - your answer goes here...

20. What is `ReactDOM`?
    - your answer goes here...

21. What is a difference between render() and ReactDOM.render()?
    - your answer goes here...

22. What is React.StrictMode?
    - your answer goes here...

23. What can I get rid of when I am ready to start customizing my React application?
    - your answer goes here...This is a long list that i'll just pull down.

24. Where can I find build instructions and other helpful React tips?
    - in the README.md that is generated from CRA

25. How do I close down the React server?
    - type in control + C in the terminal

# Resources
- [w3Schools: CLI](https://www.w3schools.com/whatis/whatis_cli.asp)
- [What Is package.json?](https://heynode.com/tutorial/what-packagejson/)
- [CRA File Structure Explained](https://medium.com/@abesingh1/create-react-app-files-folders-structure-explained-df24770f8562)
- [A quick guide to help you understand and create ReactJS apps](https://www.freecodecamp.org/news/quick-guide-to-understanding-and-creating-reactjs-apps-8457ee8f7123/)