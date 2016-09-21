# Ansible-zabbix_agentd

![N|Solid](http://www.linuxsysadmin.com.br/wp-content/uploads/2015/08/cropped-linuxsysadmin2.png)
Site: http://www.linuxsysadmin.com.br

Playbook for zabbix_agentd on Debian 8 and CentOS 7 (x86_64)

# Pré-requisito:

  - ![N|Solid](https://www.softexia.com/wp-content/uploads/2015/12/debian-logo-256x256-64x64.png) ```# apt-get install ansible```
  - ![N|Solid](http://www.linuxsysadmin.com.br/wp-content/uploads/2016/07/centos.png) ```# yum install epel-release && yum install ansible```

# Modo de uso:

Faça Download:
<br>```# wget https://github.com/elvispompeu/Ansible-zabbix_agentd/archive/master.zip```

Extraia o repositório:
<br>```# unzip master.zip```

Entre no diretório:
<br>```# cd Ansible-zabbix_agentd-master/```

Execute:
<br>```ansible-playbook -i "localhost," -c local tasks/main.yml```

Em instantes o ambiente já esta disponível com o zabbix-agent instalado e configurado corretamente.
<br>```# ps -ef | grep zabbix```
