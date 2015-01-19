docker-centos6-base-image
=========================

Docker Centos 6 base image providing:
* supervisord
* supervisorctl
* OS ruby and RVM keys
* sshd
* sudo user 'dev-ops'

docker build --no-cache -t="pauldavidgilligan/docker-centos6-base-image" .

docker run -it pauldavidgilligan/docker-centos6-base-image bash

