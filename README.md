# Instalar Servidor Ansible
* **Soportado solo en OS Linux**
* https://blog.deiser.com/es/primeros-pasos-con-ansible
* https://www.vultr.com/docs/how-to-install-and-configure-ansible-on-centos-7-for-use-with-windows-server
* https://docs.ansible.com/ansible/latest/user_guide/windows_winrm.html

# Servidores de Laboratorio
<pre>
Jaime Espallargas       windows02   192.168.17.202
Santiago Sojo           windows03   192.168.17.203
Jorge Mateos            windows04	192.168.17.204
Marta Marcos            windows05  	192.168.17.205

Dani Vila*              linux02   	192.168.17.102
Joan Figueras           linux03  	192.168.17.103
Jesús Osorio            linux04  	192.168.17.104
Felipe Roca             linux05   	192.168.17.105
Dani Hornero            linux06   	192.168.17.106
Lucas Gaiteiro          linux07   	192.168.17.107
Roberto Rodríguez       linux08   	192.168.17.108
Jose Antonio Gonzalez*  linux09   	192.168.17.109
Abel Altisent*          linux11   	192.168.17.111
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
