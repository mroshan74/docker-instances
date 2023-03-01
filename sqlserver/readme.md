## Docker

Read more on [phpMyAdmin](https://hub.docker.com/_/phpmyadmin).
> Database: `MariaDB`
> GUI: `phpMyAdmin`

&NewLine;
```sh
docker compose -f sql.yml up -d
docker compose -f sql.yml down
```

## Environment variables
&NewLine;
| Key | Value |
| ------ | ------ |
| server | db instance name like db, sql-instance ... |
| username | root |
| password | [MYSQL_ROOT_PASSWORD] |

> Note: `[MYSQL_ROOT_PASSWORD]` is required key and password for the login page refers the same.

## License

MIT

**Free Software, Hell Yeah!**
