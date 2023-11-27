### Almalinux 9 LAMP setup 

- `sudo yum install php -y`
- `php --version`
- `sudo yum install httpd -y`
- `systemctl status httpd` OR `service httpd status`
- `sudo systemctl start httpd`
- `sudo systemctl enable httpd`
- `systemctl status httpd` OR `service httpd status`
- `sudo dnf install mariadb-server -y`
- `systemctl status mariadb` OR `service mariadb status`
- `sudo systemctl start mariadb`
- `sudo systemctl enable mariadb`
- `systemctl status mariadb` OR `service mariadb status`
