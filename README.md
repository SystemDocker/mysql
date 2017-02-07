# mysql

SystemDocker unit for MySQL.

## Installation

It is assumes that before installing MySQL, you have installed [SystemDocker Common](https://github.com/SystemDocker/common). This service should be installed in the same way as any other SystemDocker service:

```
git clone https://github.com/SystemDocker/mysql.git /srv/docker/mysql
ln -s /srv/docker/mysql/units/mysql\@.service /etc/systemd/system/mysql\@.service
mkdir -p /etc/systemd/system/mysql\@.service.d
ln -s /srv/docker/common/dropins/systemdocker.conf /etc/systemd/system/mysql\@.service.d/00-systemdocker.conf
```
