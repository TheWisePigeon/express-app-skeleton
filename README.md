# express-app-skeleton

## Usage
```bash
//first you need to clone the repo
git clone https://github.com/TheWisePigeon/express-app-skeleton
//after you cloned the repo, cd into the folder
npm install
nodemon app.js
```
## Project structure

We have four folders:
Controllers, Middlewares, Models and Routes

### Controllers
This is where you will decide what goes on when a client access a route, and you do that by calling the functions you defined in your services

### Services
This is where you will write most of your logic, this code can quickly grow up and lead to spaghetti, that's why you have to separate the functions
according to which data structure they deal with

### Models
Here you define the different data structures that you will have to work with in your app. These will be mongoose schemas exported as mongoose models

### Middlewares
Think of it as helpers, something you need to do quite often but that's not really part of your buiseness logic, like check authentication state for example

### Routes
The name speak for himself, here live routes that clients interact with.

That's it for the folders

This is a basic node express app template to get you started fast with everything you need to create a fully fledged express api, from the files, to the folder and even to the deployment on Heroku.

# Deploy to heroku
I added everything you need to deploy your app to heroku, all you need to do is either use the CLI
```bash
heroku create
git remote -v
heroku push master 
```
or create a Heroku app on their [website](https://heroku.com)

I will be adding new features to this template so if you would like to stay updated, follow my github profile
Hope it can help :)
