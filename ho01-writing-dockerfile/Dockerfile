FROM postgres:17.6-alpine

ENV POSTGRES_DB = demodb
ENV POSTGRES_USER = demouser
ENV POSTGRES_PASSWORD = demopassword

#this port is postgres database access port
EXPOSE 5432 

# Step 1: Build Docker image
# docker build -t postgres-db .   # -t = tag, postgres-db = image name, "." = current directory

# Step 2: Run container from the image
# docker run -d --name postgres -p 56432:5432 postgres-db
# -d = detached mode, postgres = container name, -p = port mapping (local:container), postgres-db = image name

# docker stop postgres 
# docker container ls -a
# docker start postgres # postgres = container name 

