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
- Host-Name: content.fly
- Base-Box: ubuntu/xenial64
- Apache 2.4
  - Module: rewrite, vhost_alias, headers, expires, filter, xsendfile
- PHP 7.13
  - Module: php7.1-fpm, php7.1-cli, php7.1-common, php7.1-mbstring, php7.1-gd, php7.1-intl, php7.1-xml, php7.1-mysql, php7.1-mcrypt, php7.1-zip
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
