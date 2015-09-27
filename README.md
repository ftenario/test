# seaweed-startup

# Description
This is a startup script for SeadweedFS on Debian Linux. 

# Installation
Copy the file to /etc/init.d and create a symlink on your runlevel.
Ex. "ln -s /etc/init.d/seaweed /etc/rc3.d/S90seaweed"


# Configuration

**BINARY=/usr/local/bin/weed** //Location of your weed binary

**Log directory**

LOG=/techops/weedfs-log/ 

**Type of weed server. Set this to "volume"**

TYPE=volume 

**Location of data**

DIR=/techops/weedfs/ 

**From /etc/hostname. Change this to IP address to be able to link from the master server**

IP=$(hostname)

**Listening port for volume servers**

PORT=8080 

**Master server address**

MSERVER=localhost:9333 

**Max number of volumes**

MAX=100
**Listening port for volume servers**

PORT=8080 

**Master server address**

MSERVER=localhost:9333 

**Max number of volumes**

MAX=100
