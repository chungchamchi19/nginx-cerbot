# Introduction

This is setup ssl for localhost with nginx and docker-compose.

Happy coding!

# Create certificate
- Move to data/nginx:

```
cd data/nginx
```

- To create certificate for localhost, run: 

```
sudo openssl req -x509 -nodes -days 365 -newkey rsa:2048 -keyout nginx-selfsigned.key -out nginx-selfsigned.crt
```

# Start

- Back to root folder and start nginx and ssl for localhost, run:

```
docker-compose up
```

### Author: chungchamchi
