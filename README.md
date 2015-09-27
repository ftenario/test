# test

Change parameters accorningly.

*Location of your weed binary*

BINARY=/usr/local/bin/weed 

// Log directory
LOG=/techops/weedfs-log/ 

// Type of weed server. Set this for "volume"
TYPE=volume 

// Location of data
DIR=/techops/weedfs/ 

// From /etc/hostname. Change this to IP address to be able to link from the master server
IP=$(hostname)

// Listening port for vlume servers
PORT=8080 

// Master server address
MSERVER=localhost:9333 

// Max number of volumes
MAX=100
