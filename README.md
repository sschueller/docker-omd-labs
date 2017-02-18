omd-docker
==========

[Dockerfile](https://www.docker.com) for [Open Monitoring Distribution (OMD)](http://omdistro.org).

Run from Docker Hub
-------------------

A pre-built image is available on [Docker Hub](https://hub.docker.com/r/sschueller/omd-labs/) and can be run as follows:

    sudo docker run -d --restart=always -p 443:5000 sschueller/omd-labs:latest

OMD will become available on [http://172.X.X.X/default](http://172.X.X.X/default).
The default login is `omdadmin` with password `omd`.

To find out the IP address, run `ip addr` in the container shell.

For container shell:

    docker exec -it {containerid} bash

Based on lichti/omd-docker


