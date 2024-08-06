# teleport
## A secure file sharing and backup tool. 

A bash script that serves as a file sharing tool using the [rsync](https://wiki.archlinux.org/title/Rsync) utility. [Rsync Wikipedia](https://en.m.wikipedia.org/wiki/Rsync)
And a backup tool. 

## Current Major Features
#### 1. File Sharing
#### 2. Periodic incremental-backups and On-demand backups with cron.

### File Sharing
Currently to enable secure file sharing this only works on linux based systems and servers. 

### Backup Utility
The script intends to perform periodic backups at specified time. Add cronjob using below command to schedule incremental-backups accordingly.

```bash
crontab -e
```

Below cron expression is a schedule for every Fri 23:00

```bash
00 23 * * 05 /path/to/script/dobackup
```

