
# Goal
Create automation scripts to have a homelab configured, which will be able to run VMs, Docker Containers, Kubernetes

# Homelab ideas
- A 'starter' 3 watt 2in1 laptop server as a nextcloud server with the external raid hdd, and a media server
- Other machine (a mini PC) to serve as a proxmox server, running VMs, Docker, K8s.
- a PC with up to 5 HDD, 1TB each at least, as a storage, running NextCloud as well. 

# Starter Machine
This one is the first step to start having a local server of something. The idea is to have the external raid drive, serve a NextCloud Instance (docker), and a media server (minidlna? any with ease web access, don't need to be minimal).

Ansible can be used to install all of that, docker
or have a shell script that install docker, next cloud, and a media server

# scripts
``` sh
git clone https://github.com/juanbc42/homelab-automation.git
bash ./install_docker.sh

```

duty hulk liability geology setting ashamed graph lip