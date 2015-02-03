docker-centos6-base-image
=========================

Docker Centos 6 base image providing:
* supervisord
* supervisorctl
* OS ruby
* sshd
* sudo user 'dev-ops'

docker build --no-cache -t="registry1-eu1.moneysupermarket.com:5000/docker-centos6-base-image:1.0.7" .

docker tag registry1-eu1.moneysupermarket.com:5000/docker-centos6-base-image:1.0.7 registry1-eu1.moneysupermarket.com:5000/docker-centos6-base-image:latest

docker push registry1-eu1.moneysupermarket.com:5000/docker-centos6-base-image:latest

docker run -it registry1-eu1.moneysupermarket.com:5000/docker-centos6-base-image bash

