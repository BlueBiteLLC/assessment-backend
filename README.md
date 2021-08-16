# Blue Bite Back-end Assessment

## System Set Up

Your system needs to be able to:
 - Run `docker-compose` (you will need an up to date version of `docker` installed)
 - Run a `bash` script

Everything is dockerized so as long as you are running an up to date version of docker
then everything will work. The automated spin up maps the app port to `8000` for
convenience.

## Basic Spin-up

Run `./scripts/run-local`

This will spin up a `postgres` container and an `app` container that is running a bare
Django app on a hot-loaded debug server. After spin-up, the command will run the database
migrations. This does not seed any users or super users.
