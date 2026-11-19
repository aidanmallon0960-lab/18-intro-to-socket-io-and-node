node js can be used to run javascript outside of a web browser.
express.js works with node js as a means to run a simple web sever
a webserver is hardware or software or both that can store, process, and deliver website content

### getting set up with node
in the console, in the directory you want your program to be in, run `npm init -y`
without the `-y` you will be asked a bunch of questions about your project. the `y` just leaves the defaults.
npm - node package manager (like pip with python) used to install other js libraries into your program.
*always* .gitignore the folder node_modules
Starting and stopping the server to test can be a pain. use nodemon - `npm install --save-dev nodemon`
the `--save-dev` neabt it only needs installed when in development environments. see package.json