##### In a terminal tab, create and run the database:
- switch to the postgres user `su postgres` 
- start psql `psql postgres`
- in psql run the following:
  - `CREATE USER full_stack_user WITH PASSWORD 'password123';`
  - `CREATE DATABASE full_stack_dev;`
  - `\c full_stack_dev`
  - `GRANT ALL PRIVILEGES ON DATABASE full_stack_dev TO full_stack_user;`
- to test that it is working run `\dt` and it should output "No relations found."



use npm run dev to debug in dev