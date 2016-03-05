# IBM-Smarter-Planet

Getting Started:
- Go to https://www.jetbrains.com/student/ and select “Apply Now” at the bottom
- Enter your university email address
- Follow instructions to create account and receive activation code
- Download WebStorm

Saving the project file
- Open your Terminal
- Navigate to where you want to save the project directory
- git clone https://github.com/azaand/IBM-Smarter-Planet.git

Installing dependencies
- Ensure you have Node.js downloaded https://nodejs.org/en/download/
- Ensure you have Python downloaded https://www.python.org/downloads/
- Open WebStorm
- When it asks you to activate, select the "Register" option and enter the credentials you created before
- Open the IBM-Smarter-Planet project file
- Open the WebStorm built-in terminal
- Using AngularJS https://angularjs.org
    -Install Grunt
        -$ npm install -g grunt-cli
    -Install Bower
        -$ npm install -g bower
    -Building AngularJS
        -Visit https://github.com/angular/angular.js and fork the repository
        -Clone the AngularJS repository
            -$ git clone "git@github.com:<github username>/angular.js.git"
        -Go to the AngularJS directory
            -$ cd angular.js
        -Add the main AngularJS repository as an upstream remote to your repository
            -$ git remote add upstream "https://github.com/angular/angular.js.git"
        -Install node.js dependencies
            -$ npm install
        -Install bower components
            -$ bower install
        -Build AngularJS
            -$ grunt package

Running the local server
    -$ cd angular.js
    -$ grunt webserver
    -Go to localhost:8000 in your browser
    -All web files are located under angular.js/app
    
Using the quick start installation for the Mother sensor visit https://sen.se/developers/documentation/
    -Install the Python Sense client
    -$ pip install sense-python-client
    
 