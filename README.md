# docker_rails
Merging these two tutorials into a template for a basic Rails-on-Docker setup:

Docker's official tutorial for a docker-compose Rails setup
https://docs.docker.com/compose/rails/

From the Author of "Learn Enough to Be Dangerous"
https://www.railstutorial.org/book

Run project with:
docker-compose run web rails new . --force --no-deps --database=postgresql

Changelog (this will move to a new file later: https://keepachangelog.com/en/1.0.0/)
5/17/19
- Init and create config files for Dockerized Rails app.
- Set up bash script entrypoint.sh in local machine's /usr/bin/
