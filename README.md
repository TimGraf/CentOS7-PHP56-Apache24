# CentOS7-PHP56-Apache24
Docker Container for CentOS-7, Apache 2.4.6-40, PHP 5.6.25

docker build -t php-dev-env .

docker run --rm -p 80:80 --name php-dev-env -v <local source code>:/var/www/html php-dev-env:latest
