#React Webpack Starter App
## A Basic React Starter App with Webpack and Babel

This is a template for a React app using Webpack and Babel.

Built according to the guidelines of this Codecademy article: [React Setup, Part V: Conclusion] (https://www.codecademy.com/articles/react-setup-v)

To read the entire set of Codecademy "React Setup" articles, from Part I to Part V, visit: 

* <https://www.codecademy.com/articles/react-setup-i>
* <https://www.codecademy.com/articles/react-setup-ii>
* <https://www.codecademy.com/articles/react-setup-iii>
* <https://www.codecademy.com/articles/react-setup-iv>
* <https://www.codecademy.com/articles/react-setup-v>


##To clone it and run it on your machine:
*Note: These instructions assume that you have already installed Node.js and npm. If you have not done that already, read "React Setup, Part I" above and follow the instructions on how to install Node.js and npm before running the code below in your Terminal.*

1. Clone this repo to a directory on your local machine.
2. `cd` into the directory using the Terminal.
3. Run these commands in the Terminal:

		npm init
		npm i -S {react,react-dom}
		npm i -D babel-{core,loader} babel-preset-react
		npm i -D webpack webpack-dev-server html-webpack-plugin
		npm run build
		npm run start

4. Go to http://localhost:8080 in your browser to view your React app! As you save changes to your code, the build
will update automatically (but you will still need to refresh the page to see the changes).

Happy Coding!