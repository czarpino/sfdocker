# SfDocker

A docker compose project to easily get up and running a Symfony project. Made with a small startup team in mind looking to create a uniform dev environment.

## What's in the box

- PHP7 (configuration will pull what ever latest PHP7 version is)
- Apache Httpd v2.2 (with mod_php)
- MySQL 5.7

## Getting started

Check out this repo and create a symlink named `sf` from the Symfony project directory.

```
git clone git@github.com:czarpino/sfdocker.git
cd sfdocker
ln -s /Path/to/Symfony/project sf
docker-compose build && docker-compose up -d && docker-compose logs
```
