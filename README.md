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
