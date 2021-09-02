### recipe-app-api
Recipe app API source code.

### Run test
To run all unit tests and see if they are passed using the command
```
docker-compose run --rm app sh -c "python manage.py test && flake8"
```

### Run the app
To run the app use
```
docker-compose up
```
Then you should go to the ``` http://127.0.0.1:8000/api/user/create/ ``` firstly to create a user.

### About using the app
Firstly, you need to create your own user go to the
```
http://127.0.0.1:8000/api/user/create/
```
Then you will have a token, with help of what you can use this app because the app required token authorization.
The main address of the app is
```
http://127.0.0.1:8000/api/recipe/
```
You can check all your ingredients, tags, and recipes here. You can do create, retrieve, update, delete all your tags, ingredients, and recipes.
Also, from this page, you can manage all your recipes, ingredients, and tags. 
