# NGINX-Testing
This is a simple webpage deployed using nginx on EC2 machine

## Overview

- `nginx_install.sh` file will install `NGINX` and will enable HTTP and HTTPS requests.
   
     run the following shell command.
    ```
    sudo sh ./nginx_install.sh
    ```


- `static_page_deploy.sh` file will replace nginx default landing page with custom written html files from cloned directory.

     run the following shell command.
    ```
    sudo sh ./static_page_deploy.sh
    ```