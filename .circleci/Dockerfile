FROM kong:latest
WORKDIR /app
COPY kong.yml ~/kong/.circleci/kong.yml .
COPY . .
EXPOSE 8000
EXPOSE 8443
EXPOSE 8001
EXPOSE 8444
