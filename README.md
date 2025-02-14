# Data_Pipeline

--For starting up Postgres need to create a "data" directory within your main working directory and then map your this to your postgres directory
ex: ./data/ny_taxi_postgres_data:/var/lib/postgresql/data

--Then we need to include the "data" directory in your .dockerignore file

--This should all be in run_postgres.sh but perhaps could wrap into a docker compose file

--Run upload_data.py with the following args:  --user root --password root --host localhost --port 5432 --db ny_taxi2 --tb yellow_taxi_data --url https://d37ci6vzurychx.cloudfront.net/trip-data/yellow_tripdata_2021-01.parquet

