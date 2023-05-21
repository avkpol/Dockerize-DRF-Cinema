<h1><b>Cinema API</b></h1>
API service for cinema management written on DRF
<h3><b>Installing using GitHub</b></h3>
Install PostgreSQL and create db,
make sure you have Python3 ver.3.11
<br>

```SQL
git clone git@github.com:avkpol/Dockerize-DRF-Cinema.git

cd Dockerize_DRF_Cinema

python -m venv venv

source venv/bin/activate

pip install -r requirements.txt

set POSTGRES_HOST=<your db hostname>

set POSTGRES_NAME=<your db name>

set POSTGRES_USER=<your db username>

set POSTGRES_PASSWORD=<your db user password>

set SECRET_KEY=<your secret key>

python manage.py migrate

python manage.py runserver

```
<h3><b>Run with Docker</b></h3>

Be sure you logged in Docker and have Docker desktop app
```SQL
docker-compose build
docker-compose up
docker ps
```
<h3><b>Getting access</b></h3>


create user via api/user/register
