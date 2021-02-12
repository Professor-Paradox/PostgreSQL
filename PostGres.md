 postgres installation:

wget --quiet -O - https://www.postgresql.org/media/keys/ACCC4CF8.asc | sudo apt-key add -

echo "deb http://apt.postgresql.org/pub/repos/apt/ `lsb_release -cs`-pgdg main" |sudo tee  /etc/apt/sources.list.d/pgdg.list

sudo apt update
sudo apt -y install postgresql-12 postgresql-client-12

 sudo -i -u  postgres (to use postgres)

 psql (to go to inteface of postgres)

 \password postgres to change default password
 0000
 
sudo systemctl restart postgresql(if not connecting to postgres use this)

sudo apt update
sudo apt install pgadmin4 pgadmin4-apache2

clicking on “Add New Server”

 email some@some.com
 pgadmin4 intial password  1234
 
 
pgadmin4 web password 1234



psycopg2 install(pip install psycopg2)

libpq-dev for building a client-side application
sudo apt install libpq-dev