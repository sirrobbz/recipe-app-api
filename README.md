# Django recipe-app-api
Recipe App API source code

# Build app on docker
docker-compose build

# Start server on docker
docker-compose up

# Make Migrations
docker-compose run --rm app sh -c "python manage.py makemigrations"

# Run tests
docker-compose run --rm app sh -c "python manage.py test && flake8"

# Site Urls
Manage User: http://127.0.0.1:8000/api/user/me/
Create Token: http://127.0.0.1:8000/api/user/token/
Api Root: http://127.0.0.1:8000/api/recipe/
Recipe List: http://127.0.0.1:8000/api/recipe/recipes/
Tags List: http://127.0.0.1:8000/api/recipe/tags
Ingredient List: http://127.0.0.1:8000/api/recipe/ingredients/
