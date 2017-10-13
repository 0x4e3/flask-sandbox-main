# flask-sandbox-main
Sandbox Flask application: Proxy

[![Build Status](https://travis-ci.org/0x4e3/flask-sandbox-main.svg?branch=master)](https://travis-ci.org/0x4e3/flask-sandbox-main)

Other components:
* [Backend](https://github.com/0x4e3/flask-sandbox-users)  
* [Frontend](https://github.com/0x4e3/flask-sandbox-client)

To run containers:

```bash
$ docker-machine env dev
$ eval $(docker-machine env dev)
$ export REACT_APP_USERS_SERVICE_URL=http://DOCKER_MACHINE_IP
$ docker-compose up -d --build

```
