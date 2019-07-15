FROM kong:latest
WORKDIR /app
COPY kong.yml \git@github.com/rteam2019-project-shpel/kong/blob/master/.circleci/kong.yml
COPY . .
EXPOSE 8000
EXPOSE 8443
EXPOSE 8001
EXPOSE 8444
