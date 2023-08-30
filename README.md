# Hello and welcome to my Job search repository
Here you can find my self-study project, which contains:

![image](https://github.com/CoollGod/resume/assets/89750194/5ccadc66-766e-4204-8212-10b596766298)


3 servers with various services: 
main: Zabbix 6.0, Postgresql-14, nginx, Grafana 9.4.7, Ansible, filebeat 8.7.0, OpenVPN-server.
web: nginx, Apache, PHP, Zabbix-agent, filebeat 8.7.0
elk: PostgreSQL-12, Zabbix-agent, ELK 8.7.0 without Logstash

Main server is responsible for the site with the image that was displayed using index.html and basic html text with img src included, also zabbix-server run on it, which monitor all servers with zzbbix-agent, and then all data from zabbix goes in Grafana.
Grafana displays the disk, CPU and RAM statuses of each server.
Also OpenVPN running on this server.

Web server is responsible for blog via Wordpress on Apache2 as web server and nginx as proxy, and mail services(Postfix + Devocot)

Elk server is responsible for elasticsearch + kibana stack and postgresql database for tables in it.
