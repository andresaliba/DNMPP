# Docker NGINX ~~MySQL~~ PHP ~~PHPMyAdmin~~ (DNMPP Stack)

# Docker
This NSCC Dev Env assumes you already have Docker installed AND `docker-compose`. Review the docker-compose.yml file to see which services are currently supported/integrated.

# NGINX
This Dev Env includes a default server config for NGINX, `site.conf` which is mapped to `/etc/nginx/conf.d/default.conf`. You may want to adjust the index, server_name, root directory or php parameters to suit your prefrences. The document root is the `code` directory which is mapped to `/code`.

# PHP
The index.php should fire off `phpinfo()`. Use this to review the default PHP configuration.

# Usage
1. Clone the repo locally
2. Launch terminal and navigate to ../DNMPP
3. Run `docker-compose up`
4. Launch your browser and hit http://localhost:8080


