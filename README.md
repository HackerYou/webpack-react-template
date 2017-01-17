# Getting started

1. Fork this repository to your own Github account. You can use this boilerplate for future projects as well, so keep it around!
2. Clone your version of the repository to your local machine.
3. Once you have the code locally, run `npm install` to install all the dependencies for this project.
4. Tell React to render something. Open `entry.js`, and modify the line with `ReactDOM.render` to the following:

  ```javascript
      ReactDOM.render(<h1>Hello, world!</h1>, document.getElementById('placeholder'));
  ```
5. We'll need to install a server to get things running. Type `npm install webpack-dev-server -g` into your terminal.
6. Run `webpack-dev-server` to start your application.
7. Success! You can view your app at http://localhost:8080/webpack-dev-server/index.html
