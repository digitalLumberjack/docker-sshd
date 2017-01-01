docker-sshd
===================

Create a ssh deamon in a container.

The sshd will only allow root login with the authorized key(s) specified by the environment var `SSH_AUTHORIZED_KEYS`
Usage : 
```
docker run -e "SSH_AUTHORIZED_KEYS=your ssh key(s) here" -ti --rm digitallumberjack/docker-sshd:latest
```
