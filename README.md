## How to use

```bash
# Duplicate docker-compose's .env
$ mv .env.example .env

# Edit it and set variables
$ vim .env

# Into config folder
$ cd config

# Duplicate database's .env
$ mv database.example.env database.env

# Duplicate misskey's config
$ mv misskey/example.yml misskey/default.yml

# Edit database and misskey configs
$ vim database.env
$ vim misskey/default.ml
```