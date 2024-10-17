# Setup a Raspberry Pi SD image

In my lab I am testing a cluster of Raspberry Pi's. To make that easier
this ansible playbook will edit a downloaded OS so that the boot will not require
any interaction on my part. 

The goal is to transform raspi os to a headless boot for PiFarm use.

## State of Code

It is a personal tool and will be edited as required.  

## Insprired by

1. https://github.com/nihalgonsalves/headless-pi-setup
1. https://github.com/perrygeo/raspberry_pi
1. https://github.com/ssharpjr/rpi-headless-setup
1. https://www.raspberrypi.org/forums/viewtopic.php?t=140538
1. https://github.com/gloveboxes/Raspberry-Pi-Kubernetes-Cluster
1. https://blog.alexellis.io/test-drive-k3s-on-raspberry-pi/   (cgroup)
1. https://github.com/lucasteligioridis/raspbernetes
1. https://github.com/codesqueak/k18srpi4  (disable swap file ??)
1. 
