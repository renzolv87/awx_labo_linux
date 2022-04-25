# Instalar Servidor Ansible
* **Soportado solo en OS Linux**
* https://blog.deiser.com/es/primeros-pasos-con-ansible
* https://www.vultr.com/docs/how-to-install-and-configure-ansible-on-centos-7-for-use-with-windows-server
* https://docs.ansible.com/ansible/latest/user_guide/windows_winrm.html

# Servidores de Laboratorio
<pre>
windows01 192.168.17.3            linux01 192.168.17.4	
windows02 192.168.17.5            linux02 192.168.17.6
windows03 192.168.17.7            linux03 192.168.17.8
windows04 192.168.17.9            linux04 192.168.17.10
windows05 192.168.17.11           linux05 192.168.17.12
windows06 192.168.17.13           linux06 192.168.17.14
</pre>

## Windows setup
<pre>
C:\Windows\Ansible> .\setup.ps1 192.168.17.3 24 192.168.17.1
C:\Windows\Ansible> .\ConfigureWinRMforAnsible.ps1

borrar config:
C:\Windows\Ansible> .\clean.ps1
</pre>

## Linux setup
<pre>
cd /home/rlujan/scripts
./setup.sh linux01 192.168.17.4 24 192.168.17.1
./ansible_setup.sh

borrar config: clean.sh; ansible_clean.sh
</pre>
