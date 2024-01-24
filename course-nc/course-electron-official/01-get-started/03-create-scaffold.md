
# CREATE


## SCAFFOLD THE PROJECT

    - Electron apps follow the same general structure as other Node.js projects. Start by creating a folder and initializing an npm package.


### NPM

    $ mkdir my-electron-app && cd my-electron-app
    
    $ npm init


### YARN

    $ mkdir my-electron-app && cd my-electron-app

    $ yarn init

    
    - The interactive init command will prompt you to set some fields in your config. There are a few rules to follow for the purposes of this tutorial:

    

### MIAN.JS

    - entry point should be main.js.
    
    - author and description can be any value, but are necessary for app packaging.


### PACKAGE.JSON

    - Your package.json file should look something like this:

        {
            "name": "my-electron-app",
            "version": "1.0.0",
            "description": "Hello World!",
            "main": "main.js",
            "author": "Jane Doe",
            "license": "MIT"
        }

        "scripts": {
            "start": "electron ."
        }




## INSTALL ELECTRON TO PROJECT

    $ npm install --save-dev electron


## RUN PROJECT

    $ npm start