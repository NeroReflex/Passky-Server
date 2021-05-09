# Passky-Server
## What is Passky?
Passky is simple password manager, which works on a zero trust architecture. That means only user will be able to decrypt their passwords. So users can safelly store their passwords on any server. That means if server on where all passwords are stored get hacked, hacker won't be able to decrypt passwords and data on this server will be useless for him.

**We highly suggest you to deploy Passkey server via docker-compose for better security.**

Please be aware that this project is still work in progress.

## Installation
### Docker compose
1. Run command `docker-compose up -d`
### Manually
#### Database
1. Connect to your database server (**MySQL 8.0+ required**)
2. Copy and paste sql queries from database.sql file to your database server
3. Database is now ready to be connected with API

#### API
1. Copy and paste all .php files to your website hosting provider (**PHP 8.0+ required**)
2. Open Database.php file and edit host, database name, username and password
3. API is now ready to be connected with database
