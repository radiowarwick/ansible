# Digiplay Mount

The role sets up an NFS mount of the music file share that are exported on `dps0.medianet`.

## Role Variables

Variable | Required | Default | Choices | Comments
--- | --- | --- | --- | --- |
digiplay_mount_options | no | ro,defaults | any fstab options | see `man fstab`
digiplay_mount_dest    | no | /mnt/dps0-0 | any valid path | destination of the mount

## Dependencies

None