
# Trident Wordpress - DB

> *These scripts are hosted in the wordpress-docker-environment repo in stash*

> Generating a backup

```shell
# Will request the DB password
# Outputs DB backup to backup.sql
$ sh wordpress-docker-environment/db-backup/create-backup.sh
```

> Restoring a backup

```shell
# Will request the DB password
$ sh wordpress-docker-environment/db-backups/restore-backup.sh
```

### Database Stuff

