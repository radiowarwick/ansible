# Digiplay Mount

The `digiplay_mount` role sets up the NFS mount of the music file shares that are exported on `dps0.medianet`.

## Variables

`digiplay_mount_options` specifies the mount options, by default this is `ro,defaults`
`digiplay_mount_dest` speicifies the mount destination path, by default this is `/mnt/dps0-0`