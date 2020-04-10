# docker-unprivileged-nginx
unprivileged nginx Dockerfiles

for example
```
docker build -t nginx:non-root .
docker run -d -p 8080:8080 nginx:non-root
```
