# Raspberry Pi Time

A little script to mount your raspberry pi's filesystem over ssh using sshfs.

## Uage


Install SSHFS

```
sudo apt-get install sshfs
```

Mount Filesystem using the start.sh script. This will need to be edited if you have a different ip or username.

```
sh mount.sh
```

Unmount the filesystem

```
sh unmount.sh
```
