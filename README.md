
# USAGE in your box
This NFS storage has only 190 GB. Use this storage as your own risk.   
This NFS server can be used as testing your manifests with storage.    
Cleanup process can happen when space is limited. NFS server 10.86.1.244 sit on engcloud.prv.suse.net.

# In your client machine:
sudo mount -t nfs 10.86.1.244:/var/nfs /mnt

# There are two usage of NFS storage
1. NFS PersistentVolume - nfs-pv

2. NFS StorageClass - nfs - sc

