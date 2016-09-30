<img src="https://raw.githubusercontent.com/Merryfurr/SapphireOS/master/pictures/BannerGithub_Others.png" alt="SapphireOS Logo" width="256" height="128">

A shiny new UNIX*

## Build & Run using [Vagrant](https://www.vagrantup.com/ "The Vagrant Homepage")

Make sure you have both Vagrant installed and this repo cloned (and an open terminal in it's folder)

Then run the following commands (ignore comment lines starting with ```#```):

```bash
# Starts Vagrant VM
vagrant up

# SSH into machine
vagrant ssh

# Once SSHed
cd /vagrant

# Build kernel, userland ...
make all

# Run emulation
make emulate
```

(Based on SamyPesse's project)
