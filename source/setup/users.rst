Users
#####

Adding a User
-------------

Once you've initially installed Postgres you should be able to connect almost immediately with `psql -h localhost`. This will put you inside your database to begin working. Of course the next step before 

..code::SQL

   craig=# CREATE USER craig WITH PASSWORD 'Password';
   CREATE ROLE
   craig=# CREATE DATABASE pgguide;
   CREATE DATABASE
   craig=# GRANT ALL PRIVILEGES ON DATABASE pgguide to craig;
   GRANT

