<h1><b>Cinema API</b></h1>
API service for cinema management written on DRF
<h3><b>Installing using GitHub</b></h3>
Install PostgreSQL and create db

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
