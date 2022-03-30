<img src="icon.png" align="right" />

# KONG-API-GATEWAY 

[![Awesome](https://img.shields.io/badge/Docker-2CA5E0?style=for-the-badge&logo=docker&logoColor=white)](https://github.com/sindresorhus/awesome#readme)


This repository contain Kong Api gateway configuration for docker.

## Installation

Run command below :
```
     docker-compose up
```
You can add "-d" to run in background
```
     docker-compose up -d
```

if you hit the /api path actually domain is forwarding to url https://yourdomain.com directly, without '/api' path

example :

hit
```
     localhost:8000/api/login
```

result :
```
     https://yourdomain.com/login
```

## Reference

- https://hub.docker.com/_/kong



