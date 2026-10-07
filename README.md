# tws-eb-single-tier

A minimal single-tier static web application served by Nginx, designed for Elastic Beanstalk deployment experiments.

## Build the Docker Image

```bash
docker build -t tws-eb-single-tier .
```

## Run the Container

```bash
docker run -d -p 8081:80 --name tws-app tws-eb-single-tier
```

## Open in Browser

Open your browser and navigate to:

```text
http://localhost:8081
```
