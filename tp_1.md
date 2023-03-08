# TP_1 Docker Jonathan Philippe

## Exercice 1

### A - docker pull nginx
### B - docker images
![Terminal](/img/terminal.png)
### C - index.html créer
### D - docker run -d -p 8080:80 -v /Users/jonathanphilippe/Documents/Ecole/Docker/Docker_TP_1/index.html:/usr/share/nginx/html/index.html --name my-nginx nginx
![Index_html_on_nginx](/img/index_html_on_nginx.png)
### E -
- docker rm -f my-nginx
- docker run --name my-nginx -p 8080:80 nginx
- docker cp /Users/jonathanphilippe/Documents/Ecole/Docker/Docker_TP_1/index.html my-nginx:/usr/share/nginx/html/index.html
- docker start my-nginx
![Index_html_on_nginx](/img/index_html_on_nginx.png)