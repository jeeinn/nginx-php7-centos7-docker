# Build

```bash
docker build -t uveio/nginx-php-docker .
```

# Run Docker Container

```bash
docker run -d --name nginx-php -p 80:80 -v /Users/linhua/projects/uveio/nginx-php7-centos7-docker/nginx/logs:/var/nginx/logs -v /Users/linhua/projects/uveio/nginx-php7-centos7-docker/nginx/html:/usr/local/nginx/html -v /Users/linhua/projects/uveio/nginx-php7-centos7-docker/nginx/conf:/usr/local/nginx/conf uveio/nginx-php-docker
```
