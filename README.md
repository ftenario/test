# test

# seaweed-startup

This is a startup script for Debian Linux. Copy the file to /etc/init.d and create a symlink on your runlevel.

Change parameters accorningly.

**Location of your weed binary**

BINARY=/usr/local/bin/weed 

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
