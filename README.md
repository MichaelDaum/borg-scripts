# borg-scripts
my scripts to handle borg backups

- cp -a `etc/borg` to `/etc/borg`
- cp `bin/*` to `/usr/local/sbin`
- edit `/etc/borg/config` 
- edit `/etc/borg/passphrase`
- `borg-init`
- ln -s `/usr/local/sbin/borg-backup` `/etc/cron.daily`

more docu at https://borgbackup.readthedocs.io

