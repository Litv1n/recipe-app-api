### recipe-app-api
Recipe app API source code.

### Run test
To run all unit tests go to the root directory and run:
```
docker-compose run --rm app sh -c "python manage.py test && flake8"
```

### Run the app
Run the app by using:
```
docker-compose up
```

### Usage
You need to create your own user with unique token before using the API. To do that go to the:
```
http://127.0.0.1:8000/api/user/create/
```
Then you will have a token, use it in header of your request to access the data.
The root dir address is:
```
http://127.0.0.1:8000/api/recipe/
```
You can check all your ingredients, tags, and recipes here. You can do create, retrieve, update, delete all your tags, ingredients, and recipes.
Also, from this page, you can manage all your recipes, ingredients, and tags. 
