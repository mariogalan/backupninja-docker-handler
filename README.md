# backupninja docker handler

A handler for backup docker containers with [backupninja](https://0xacab.org/riseuplabs/backupninja)

Based on the information contained on this page on [how to backup docker containers](https://bobcares.com/blog/docker-backup/)

# Installation instructions
- Clone or download this repository
- Copy the file "docker" to /usr/share/backuninja
- Copy the file "50.docker" to /etc/backup.d
- Edit the file /etc/backup.d/50.docker to add your own container ids