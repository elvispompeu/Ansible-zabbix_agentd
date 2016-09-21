# Ansible-zabbix_agentd

Playbook for zabbix_agentd on Debian 8 and CentOS 7 (x86_64)

# Pré-requisito:

Debian 8: apt-get install ansible
CentOS 7: yum install epel-release && yum install ansible

# Modo de uso:

Faça Download e extraia o repositório:
## wget https://github.com/elvispompeu/Ansible-zabbix_agentd/archive/master.zip
## unzip master.zip
## cd Ansible-zabbix_agentd-master/

Execute: 
## ansible-playbook -i "localhost," -c local zabbix-agent.yml

Em instantes o ambiente já esta disponível com o zabbix-agent instalado e configurado corretamente.

# ps -ef | grep zabbix
zabbix    4367     1  0 14:33 ?        00:00:00 /usr/sbin/zabbix_agentd -c /etc/zabbix/zabbix_agentd.conf
zabbix    4368  4367  0 14:33 ?        00:00:00 /usr/sbin/zabbix_agentd: collector [idle 1 sec]          
zabbix    4369  4367  0 14:33 ?        00:00:00 /usr/sbin/zabbix_agentd: listener #1 [waiting for connection]
zabbix    4370  4367  0 14:33 ?        00:00:00 /usr/sbin/zabbix_agentd: listener #2 [waiting for connection]
zabbix    4371  4367  0 14:33 ?        00:00:00 /usr/sbin/zabbix_agentd: listener #3 [waiting for connection]
zabbix    4372  4367  0 14:33 ?        00:00:00 /usr/sbin/zabbix_agentd: active checks #1 [idle 1 sec]   
(...)
# zabbix_agentd --version
zabbix_agentd (daemon) (Zabbix) 3.0.4
(...)
