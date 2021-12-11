# Introduction

This is setup ssl with nginx and docker-compose.

Happy coding!

# Setup
- Change `server_name` information in `data/nginx/app.conf`

- Change `domain_name` and `email` information in `init-letsencrypt.sh`

- Bash enscrypt:

```
chmod +x init-letsencrypt.sh
```

```
sudo ./init-letsencrypt.sh
```

# Start
- To start nginx and certbot, run:

```
docker-compose up
```

### Author: chungchamchi
