django-deploy
=============

basic tools (including fab script) to install Django, nginx, gunicorn

Initial installation
=============

#
apt-get update
apt-get upgrade
apt-get install mc htop git

useradd -d /opt/django -m -r django
passwd django

mkdir -p /opt/django
mkdir -p /opt/django/apps
mkdir -p /opt/django/logs
mkdir -p /opt/django/logs/nginx
mkdir -p /opt/django/logs/apps
mkdir -p /opt/django/configs
mkdir -p /opt/django/scripts
mkdir -p /opt/django/htdocs
mkdir -p /opt/django/tmp
mkdir -p /opt/django/configs/nginx
mkdir -p /opt/django/configs/supervisord
mkdir -p /opt/django/apps/my_app
