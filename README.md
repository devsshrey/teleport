# dobackup
periodic incremental-backup script

The script intends to perform periodic backups at specified time. Add cronjob accordingly using below command

```bash
crontab -e
```

Below cron expression is a schedule for every Fri 23:00

```bash
00 23 * * 05 /path/to/script/dobackup
```

