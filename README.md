# APP-CMS.
- **Lizenz**: Duale Lizenz AGPL v3 / Properitär
- **Webseite**: http://www.das-app-cms.de

## Die APP-CMS Plattform

- **Server**: https://github.com/area-net-gmbh/appcms-server

## Tools und mehr

- Vagrant-Umgebung für Server: https://github.com/area-net-gmbh/appcms-vagrant
- Download + Dokumentation: http://www.das-app-cms.de

# Vagrant-Umgebung

Mit dieser Vagrant-Umgebung kann der APP-CMS Server auf einer lokalen Entwicklungsmaschine betrieben werden.

## Entwicklungsumgebung

- IP-Adresse: 192.160.14.15
- Host-Name: appcms.dev
- Base-Box: ubuntu/trusty64
- Apache 2.4
  - Module: rewrite, vhost_alias, headers, expires, filter, xsendfile
- PHP 5.6
  - Module: php5-cli, php5-intl, php5-mcrypt, php5-curl, php5-imagick, php5-gd, php5-mysql
- MySQL 5.6

## Installation und erste Schritte

- Vagrant installieren: https://www.vagrantup.com/docs/installation
- Ansible installieren: http://docs.ansible.com/ansible/latest/intro_installation.html
- APP-CMS Server herunterladen und entpacken
- Vagrant-Umgebung in gleichem Verzeichnis abspeichern

## Start und Login

- Starten der Vagrant-Box über: __vagrant up__
- SSH-Login per: __vagrant ssh__
- APP-CMS im Browser aufrufen: http://appcms.dev
