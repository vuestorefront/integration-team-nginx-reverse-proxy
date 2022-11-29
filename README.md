## What is it?
This is the simple nginx-based reverse proxy for a local development of a multistore integrations.
## Preparation
Open `nginx.conf` file and adjust to your needs. Each project and environment will require a different setup, but it should be as easy as adjusting hosts and ports. Inside the file there is a small guidance of what sohuld be adjusted.

**linux**: if you are a linux user, in addition, please uncomment lines 9-10 in the `docker-compose.yml` file
## How to run?
Simply execute `docker-compose up -d` command in the directory with `docker-compose.yml` file.