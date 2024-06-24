# Commerce API 
Ecommerce API is a RESTful API 

## Technology Stack
- [Python](https://www.python.org/ "python")
- [Postgres](https://www.postgresql.org/ "Postgres")
- [Django](https://www.django-rest-framework.org/ "Django")

## Formatter or Linters
- [Flake8](https://flake8.pycqa.org/en/latest/index.html# "Flake8")
- [Black](https://black.readthedocs.io/en/stable/ "Black") 
- [Isort](https://pycqa.github.io/isort/ "Isort")


## How to set up locally using Docker container - **Recommended**
### Prerequisite
- Make sure **Docker** is installed locally. *Checkout installation here* [Docker](https://www.docker.com/ "Docker")
- Make sure **Postgres** is installed locally. *Checkout installation here* [Postgres](https://www.postgresql.org/ "Postgres")

1. Clone the project.
```sh
 git clone https://github.com/CyrilBaah/commerce-api.git
```
```sh
 cd commerce-api
```
2. Change the env.example file to .env 
3. Run 
```sh
 docker-compose build --no-cache
```
4. Run 
```sh
 docker-compose build up
```