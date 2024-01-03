# aws-ebs-volume-size

if you modify volume increase 

step by step run these commands

```
sudo lsblk

growpart /dev/nvme0n1 1

xfs_growfs -d /

resize2fs /dev/nvme0n1p1
```
