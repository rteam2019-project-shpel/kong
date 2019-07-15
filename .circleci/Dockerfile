FROM kong:latest
WORKDIR /app
COPY $(pwd)/.circleci/kong.yml .
COPY . .
EXPOSE 8000
EXPOSE 8443
EXPOSE 8001
EXPOSE 8444
