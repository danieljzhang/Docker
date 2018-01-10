# Install Docker CE on Fedora

**OS: Fedora 26**

**Install using the repository**

**Set up the repository**

https://docs.docker.com/engine/installation/linux/docker-ce/fedora/#install-docker-ce

**Install Docker CE**

$ sudo dnf install docker-ce

**Start Docker**

$ sudo systemctl start docker

**Verify that Docker CE is installed correctly by running the hello-world image.**

$ sudo docker run hello-world

**Manage Docker as a non-root user**

https://docs.docker.com/engine/installation/linux/linux-postinstall/

Verify that you can run docker commands without sudo .