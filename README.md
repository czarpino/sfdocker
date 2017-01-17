# Symfony Docker Env

Check out this repo and create a symlink named `sf` from the Symfony project directory.

```
git clone git@github.com:czarpino/sfdocker.git
cd sfdocker
ln -s /Path/to/Symfony/project sf
docker-compose build && docker-compose up -d && docker-compose logs
```
