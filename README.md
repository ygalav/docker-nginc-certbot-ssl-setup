# docker-nginx-certbot-ssl-setup

This repo represents simple setup of SSL Certificate for Java Application (or anything else) under docker + nginx + LetsEncrypt (certbot).
Feel free to use if needed.

Developed on a dase of this article: https://medium.com/@pentacent/nginx-and-lets-encrypt-with-docker-in-less-than-5-minutes-b4b8a60d3a71


### Steps
- Update `myhost.com` in `nginx.conf` and set your hosts
- Update `domains, email, data_path` in `init-letsencrypt.sh`
- run `. ./init-letsencrypt.sh` 