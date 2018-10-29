# PostgreSQL 10

Day to day command

pg_hba.conf

## User Management

### Show user
``` \du ```


### Creating User
Option 1
``` $ sudo -u postgres createuser <username> ```

***or***

Option 2

### Creating Database
``` $ sudo -u postgres createdb <dbname> ```

### Using query
```
CREATE DATABASE yourdbname;
CREATE USER youruser WITH ENCRYPTED PASSWORD 'yourpass';
GRANT ALL PRIVILEGES ON DATABASE yourdbname TO youruser;
```

## QUERY

