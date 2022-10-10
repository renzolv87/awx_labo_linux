# Instalar Servidor Ansible
* **Soportado solo en OS Linux**
* https://blog.deiser.com/es/primeros-pasos-con-ansible
* https://www.vultr.com/docs/how-to-install-and-configure-ansible-on-centos-7-for-use-with-windows-server
* https://docs.ansible.com/ansible/latest/user_guide/windows_winrm.html

# Servidores de Laboratorio
<pre>
Enrique Bellido         windows02   192.168.17.202
Marcos Sánchez          windows03   192.168.17.203

Gonzalo de la Torre     linux02     192.168.17.102
David Pulido            linux03     192.168.17.103
Guillermo Chacón        linux04     192.168.17.104
Juan Villegas           linux05     192.168.17.105
Miguel Martinez         linux06     192.168.17.106
Francisco Simón         linux07     192.168.17.107
Juan De Dios Navarro    linux08     192.168.17.108
Miguel Angel Maldonado  linux09     192.168.17.109
Manuel Arco             linux10     192.168.17.110
Mª Carmen Delgado       linux11     192.168.17.111
Carlos Javier Pérez     linux12     192.168.17.112
</pre>

## Windows setup
<pre>
cd C:\Windows\Ansible
C:\Windows\Ansible> .\setup.ps1 192.168.17.2XX 24 192.168.17.1
C:\Windows\Ansible> .\ConfigureWinRMforAnsible.ps1

borrar config:
C:\Windows\Ansible> .\clean.ps1
</pre>

## Linux setup
<pre>
cd /home/rlujan/scripts
./setup.sh linuxXX 192.168.17.1XX 24 192.168.17.1
./ansible_setup.sh

borrar config: clean.sh; ansible_clean.sh
</pre>
