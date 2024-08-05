Solution for Ubuntu / xdebug
change this line in docker-compose-dev.yml under 'environment':
- XDEBUG_CONFIG=client_host=xxx.xxx.xxx.xxx discover_client_host=0 client_port=9003 idekey=PHPSTORM log=/var/log/apache2/xdebug.log

client_host=xxx.xxx.xxx.xxx is the local IP from windows machine

<!---
ElSethos2024/ElSethos2024 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
