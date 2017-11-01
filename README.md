# NodeExpresEjs
Demo web app using node js, express and ejs using express-generator boiler-plate.


Node js express ejs setup
--------------------------------

This walkthrough will give a basic idea for quick setup of nodejs application using express framework and EJS as view template. For quick design are going to use boiler plate provided by express-generator package.


Required
-----------
NodeJs and npm should be installed and running on your machine. Check the version by typing the below commands in the terminal.

> node -v
v6.9.1

>nmp -v
3.10.8

For generating the stub we need to install express-generator.

>npm install -g express-generator

If you faces permission error do sudo on the command.

>sudo npm install -g express-generator

N.B.
-g flag specifies you are installing the package globally.

Now we are going to create express application using express-generator boiler plate.

>express -e NodeDemoExample

Usage: express [options] [dir]

  Options:

    -h, --help           output usage information
        --version        output the version number
    -e, --ejs            add ejs engine support
        --pug            add pug engine support
        --hbs            add handlebars engine support
    -H, --hogan          add hogan.js engine support
    -v, --view <engine>  add view <engine> support (ejs|hbs|hjs|jade|pug|twig|vash) (defaults to jade)
    -c, --css <engine>   add stylesheet <engine> support (less|stylus|compass|sass) (defaults to plain css)
        --git            add .gitignore
    -f, --force          force on non-empty directory


install dependencies:

>cd express_example && npm install

run the app:

>DEBUG=express_example:* npm start

Normally when you are working in a nodejs application, you need to restart teh app again and again once you are submitting any changes. If you use nodemon package, it will build and re-deploy the application. No need to restart app.

>npm install -g nodemon

>DEBUG=express_example:* nodemon

For windows 
--------------
install dependencies:
  > cd NodeExpressEjs && npm install

run the app:
  > SET DEBUG=nodeexpressejs:* & npm start
  > SET DEBUG=nodeexpressejs:* & nodemon








