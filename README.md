# Docker Databases Compose File

A simple Docker Compose File that auto-generates and configures different databases:

- `mysql` ( persistent data )
- `phpmyadmin` ( defaults to mysql )
- `postgresql` ( persistent data )
- `pgadmin` ( defaults to postgresql )

Any extra databases may be added in the future.

### Installation:
1. `git clone https://github.com/thimvanamersfoort/docker-databases`
2. `cd docker-databases`
3. `mv .example.env .env`
4. Fill in the appropriate values in your `.env` file.
5. `docker compose up -d`