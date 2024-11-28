## mariadb:latest & phpmyadmin

### For run

- copy .env.example to .env
- enter your data for environment variables in .env
- put yours dump.sql in the directory ./init
- clear the directory ./data if you previously imported data and you need to replace it
- give/check your permissions (need write on ./date)
- execute in the project directory: `docker compose up`
- for rebuilding: `docker compose up --build --force-recreate --no-deps`