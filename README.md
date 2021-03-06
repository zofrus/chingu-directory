# chingu-directory
the directory page for chingu

## Install

You must have npm installed in your local machine, node comes with npm so if you want you can install it from [Node official website](https://nodejs.org/en/)

clone the repo on your local machine thru the command line

`git clone https://github.com/Chingu-cohorts/chingu-directory/`

and then run `npm i` to install all the dependencies needed to run this project

after that if you use a *linux OS* set this script inside `package.json` and run `npm start`, reach _localhost:8080_ on your browser to see the project.

```
"scripts": {
    "start": "NODE_ENV=development webpack-dev-server",
```

if otherwise you use a *windows OS* just open `package.json` on your editor and modify the start script as follows before running `npm start` to see the website on _localhost:8080_.

```
"scripts": {
    "start": "set NODE_ENV=development & webpack-dev-server",
```


## Code guidelines

This repository follows [AirBnB Javascript style guide](https://github.com/airbnb/javascript) so be sure to check your code before sending a pull request, comments are also required on a lot of stuff, be sure to explain your code so others can work better.
