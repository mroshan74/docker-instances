## Docker

Read more on [phpMyAdmin](https://hub.docker.com/_/phpmyadmin).
> Database: `MariaDB`
> GUI: `phpMyAdmin`

&NewLine;
```sh
docker compose -f sql.yml up -d
docker compose -f sql.yml down
```

## Login creds
&NewLine;
| Input | Value |
| ------ | ------ |
| server | db instance name like db, sql-instance ... |
| username | root |
| password | [MYSQL_ROOT_PASSWORD] |

> Note: `[MYSQL_ROOT_PASSWORD]` is required key and password for the login page refers the same.

## ENV
&NewLine;
| Key | Value |
| ------ | ------ |
| MYSQL_ROOT_PASSWORD | securepassword |
| PMA_ARBITRARY | 1 |
| PMA_HOST | db instance name like db, sql-instance |

## License

MIT

**Free Software, Hell Yeah!**
