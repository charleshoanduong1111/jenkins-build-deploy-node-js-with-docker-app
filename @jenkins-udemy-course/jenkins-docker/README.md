# Jenkins docker
* Jenkins CI with docker client

For Dockerfile
Hint: If you're not using the same DigitalCocean Ubuntu setup. 
Make sure to change the 999 on line 9 with the
GID (group ID) your docker group has on your system, To check run:
cat /etc/group | grep docker or alternatively: getent group docker

to find the gid of docker on your system

NOTE: 

docker --version

Docker ID is just the docker username.
Dicker GID is docker

Docker Group ID.
Run this command from an administrator command window to add your user id to the 
docker-users group and log back into your user account for it to take effect.

net localgroup docker-users "your-user-id" /ADD
your-user-id is your local Windows user name. You can determine this by looking 
at the folder name under C:\Users\ .