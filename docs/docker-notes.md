
# Docker Notes — Day 9

## Docker Version
Client:
 Version:           20.10.24+dfsg1
 API version:       1.41
 Go version:        go1.19.8
 Git commit:        297e128
 Built:             Sat Jan  3 00:46:39 2026
 OS/Arch:           linux/amd64
 Context:           default
 Experimental:      true

Server:
 Engine:
  Version:          20.10.24+dfsg1
  API version:      1.41 (minimum version 1.12)
  Go version:       go1.19.8
  Git commit:       5d6db84
  Built:            Sat Jan  3 00:46:39 2026
  OS/Arch:          linux/amd64
  Experimental:     false
 containerd:
  Version:          1.6.20~ds1
  GitCommit:        1.6.20~ds1-1+deb12u2
 runc:
  Version:          1.1.5+ds1
  GitCommit:        1.1.5+ds1-1+deb12u1
 docker-init:
  Version:          0.19.0
  GitCommit:      

## Hello World Test

  Hello from Docker!
This message shows that your installation appears to be working correctly.

To generate this message, Docker took the following steps:
 1. The Docker client contacted the Docker daemon.
 2. The Docker daemon pulled the "hello-world" image from the Docker Hub.
    (amd64)
 3. The Docker daemon created a new container from that image which runs the
    executable that produces the output you are currently reading.
 4. The Docker daemon streamed that output to the Docker client, which sent it
    to your terminal.

To try something more ambitious, you can run an Ubuntu container with:
 $ docker run -it ubuntu bash

Share images, automate workflows, and more with a free Docker ID:
 https://hub.docker.com/

For more examples and ideas, visit:
 https://docs.docker.com/get-started/  


##  output: docker logs pg-prework
 2026-03-05 08:52:42.660 UTC [1] LOG:  database system is ready to accept connections
