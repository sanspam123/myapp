# MyApp

docker-compose run app alembic revision --autogenerate -m "New Migration" <br>
docker-compose run app alembic upgrade head

docker-compose up
