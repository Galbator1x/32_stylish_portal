# Shared CSS Library

Test stand for developing a new CSS library. Nginx looks for a local version of the main style file in the directory
on the developer's machine and proxy the request to the production server if the file does not exist.

## How to Test

[Install nginx](https://nginx.org/en/docs/install.html) and run commands:
```
$ git clone {{the link to this repository}} {{project name}}
$ cd {{project name}}
$ sudo ln -s $(pwd)/nginx.conf /etc/nginx/nginx.conf
$ sudo service nginx restart
```
Go to [localhost:8001](http://localhost:8001/) and [localhost:8002](http://localhost:8002/)

## Project Goals

The code is written for educational purposes. Training course for web-developers - [DEVMAN.org](https://devman.org)
