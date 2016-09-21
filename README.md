# Ansible-zabbix_agentd

![N|Solid](http://www.linuxsysadmin.com.br/wp-content/uploads/2015/08/cropped-linuxsysadmin2.png)

Playbook for zabbix_agentd on Debian 8 and CentOS 7 (x86_64)

# Pré-requisito:

  - ![N|Solid](http://www.linuxsysadmin.com.br/wp-content/uploads/2015/08/debian.png) ```# apt-get install ansible```
  - ![N|Solid](http://www.linuxsysadmin.com.br/wp-content/uploads/2016/07/centos.png) ```# yum install epel-release && yum install ansible```

# Modo de uso:

Faça Download:
```# wget https://github.com/elvispompeu/Ansible-zabbix_agentd/archive/master.zip```

Extraia o repositório:
```# unzip master.zip```

Entre no diretório:
```# cd Ansible-zabbix_agentd-master/```

Execute:
```# ansible-playbook -i "localhost," -c local zabbix-agent.yml```

Em instantes o ambiente já esta disponível com o zabbix-agent instalado e configurado corretamente.

```# ps -ef | grep zabbix```
