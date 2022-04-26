FROM nginx:1.21.6

COPY nginx.conf /etc/nginx/nginx.conf
COPY default.conf /etc/nginx/conf.d/default.conf
# COPY public /usr/share/nginx/html

# WORKDIR /app

# nginx user must own the cache directory to write cache
RUN chown -R 1000:0 /var/cache/nginx \
    && chmod -R g+w /var/cache/nginx

USER 1000
