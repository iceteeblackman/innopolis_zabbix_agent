# innopolis_zabbix_agent


docker run -d --name zabbix-agent --restart unless-stopped -e ZBX_HOSTNAME="nginx001" -e ZBX_SERVER_HOST="10.90.138.204" -d -p 0.0.0.0:10050:10050 zabbix/zabbix-agent:latest
