# SQL+Python Docker Environment
**Description**: Dockerfiles and docker compose for SQL and Python environment for STAT 315/CSCE 305/ECEN 360

## Quick start guide
1. Download zipped folder containing all files in this repository.
2. Unzip folder and store in local directory of your choosing.
3. In a terminal window, navigate to the local directory containing `docker-compose.yml`.
4. Run the command `docker compose up`.  The Docker images will be downloaded to your system and containers will be created accordingly.
5. Open a web browser window and type `localhost:5050` to open pgAdmin4 GUI to interact with the database.
6. In a different web browser tab, copy and paste the custom URL provided in the terminal window to access the Jupyter notebook environment to interact with the database.
7. Download any table of your choice, save it in your local repo as 'my_secret_id_mytable.db', and push it to this github repo. Here my_secret_id is an alias for your "secret STAT315 id". 
