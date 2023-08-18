*FIRST STEPS TO RUN ON DEV ENVIRONMENT*

Go to te directory of the application and run

```
docker compose up --build
```
This will build and run the necessary containers to run the application.



IF IS THE FIRST TIME RUNNING then you will need to create a database (you can use you favorite platform like DBeaver, PGAdmin, DataGrip or the CLI) and apply the migrations to the Database, if has any to be applied

```bash
#open the bash of the backend container
docker exec -ti sherlock-holmes-watsonn-backend-1 bash

#once you've entered the bash of the container run the migrations command
alembic upgrade head
```
