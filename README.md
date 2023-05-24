# Cinema API
API service for cinema management written on DRF
## Installing using GitHub
1. Install PostgreSQL and create db,
   make sure you have Python3 ver.3.11
<br>
2. in Terminal run:

```SQL
git clone git@github.com:avkpol/Dockerize-DRF-Cinema.git

cd Dockerize_DRF_Cinema

python -m venv venv

source venv/bin/activate

pip install -r requirements.txt
    
```
3. create .env file in your project's directory

```SQL
touch .env
```
then open .env and provide following information


```SQL
POSTGRES_HOST=<your db hostname>

POSTGRES_NAME=<your db name>

POSTGRES_USER=<your db username>

POSTGRES_PASSWORD=<your db user password>

SECRET_KEY=<your secret key>(if needed)

```

## Run with Docker

Be sure you logged in Docker and have Docker desktop app

```SQL
docker-compose build
docker-compose up
docker ps 
```
(to see if the container(s) is running

## Getting access

create user via api/user/register/<br>
create token via /api/user/token/
