# Blog da Lu

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 13.0.4,
​	 json-server:^0.17.0,
    @fortawesome: ^5.15.4,
    bootstrap: ^5.1.3,
    jquery: ~3.4.1,
    popper.js: ^1.16.1
    node.js: v10.19.0

npm init -y         create file package.json
npm i json-server   install json-server.json

Installing @ Angular/cli and creating blog directory for frontend
    • npm i -g @angular/cli
    • ng new blog
    • cd blog
    • ng serve -o

Installing 
    Bootstrap: npm i bootstrap 
    JQuery: npm i jquery@~3.4.1
    Popper: npm i popper.js
    Awesome's Font: ng add @fortawesome/angular-fontawesome
       ◉ Free Solid Icons
       ◉ Free Regular Icons
       ◉ Free Brands Icons
    Node.js:
        Simply put, Node.js is a server-side execution environment that allows JavaScript to work without the client. To use it, you need to install node.js - as they are bundled together.
            ◦  sudo apt-get install curl
            ◦ curl -fsSL https://deb.nodesource.com/setup_lts.x | sudo -E bash -
            ◦ sudo apt-get install -y nodejs
    ng2-search-filter: npm i ng2-search-filter --save
    ng2-search-filter is completely free and open-source.

## Development server

Run 'ng serve -o' for a dev server - frontend. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

Run 'npm start' for a dev server - backend. Navigate to `http://localhost:3000/posts`. The app will automatically reload if you change any of the source files.

## Generate components

Run 'ng g c component-name' to generate a new component. Ex.: ng g c home
Components: home, footer, feed, contato and navbar 
Some components use bootstrap code (https://getbootstrap.com/)

Obs.: in the tsconfig.json file you can find the strict use configuration ("compilerOptions" / "strict": false). A program that worked correctly without "strict mode" may stop working with "strict mode" active. Furthermore, "strict mode" is not supported by all browsers, and therefore care must be taken as code that works correctly with "strict mode" enabled may not work in browsers that do not support "strict mode".

