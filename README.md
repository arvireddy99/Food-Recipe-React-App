# A React APP for providing Food recipes alongwith its associated Calories, images and many more

### 1. To use:
   Install node.js
   
To install React globally (remove -g if locally)
    
    npx install create-react-app -g

### 2. Navigate to the recipe_app directory
    
    ./recipe_app

### 3. To Run the app :
    
    npm start

### 3. The website will run the development server in your system , Tadah!

### 4. It uses an API which user can call 5 get requests/min 


Commands:

Local:
    cd Food-Recipe-React-App
    npm i

Deployment:
    docker build -t food-recipe-react-app .
    docker run -p 3000:80 food-recipe-react-app
    heroku login
    heroku create food-recipe-react-app
    git commit -am "Configure secure headers and static buildpacks"
    heroku buildpacks:set heroku/nodejs
    heroku buildpacks:add https://github.com/heroku/heroku-buildpack-static.git
    git push heroku master
