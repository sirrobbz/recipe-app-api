# recipe-app-api
Recipe App API source code

# Start server on docker
docker-compose up

# Run tests
docker-compose run --rm app sh -c "python manage.py test && flake8"
