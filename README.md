# Instalar Servidor Ansible
* **Soportado solo en OS Linux**
* https://blog.deiser.com/es/primeros-pasos-con-ansible
* https://www.vultr.com/docs/how-to-install-and-configure-ansible-on-centos-7-for-use-with-windows-server
* https://docs.ansible.com/ansible/latest/user_guide/windows_winrm.html

# Servidores de Laboratorio
<pre>
Gustavo Zafra   windows02   192.168.17.202
Roberto Bermejo windows03   192.168.17.203

Josep Mª Bean   linux02   192.168.17.102
Yolanda Vera    linux03   192.168.17.103
Diana Bolivar   linux04   192.168.17.104
Aitor Oliveira  linux05   192.168.17.105
Diego Gomez     linux06   192.168.17.106
Roger Roca      linux07   192.168.17.107
Sergio Garrido  linux08   192.168.17.108
Xavier Gadea    linux09   192.168.17.109
Javier Garcia   linux10   192.168.17.110
Pablo Bazan     linux11   192.168.17.111
</pre>

## Windows setup
<pre>
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
