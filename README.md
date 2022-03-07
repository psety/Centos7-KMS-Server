# Centos7-KMS-Server
Installation Steps

1- Download the Centos7 iso 

2- Install the Centos7. I prefer to install Centos7 with Gnome GUI.

3- Create a root connection and disable the firewall 

3.1 - $ systemctl stop firewalld

3.2 - $ systemctl disable firewalld

4- Create an install.sh file and copy the KMSScript into it. 

4.1 - $ cd /home/

4.2 - $ nano install.sh

4.3 copy the script into it and save it. 

4.3 - $ chmod 755 install.sh

4.4 - $ ./install.sh


Windows Activation 

5 - Open the CMD as administrator

5.1 - # slmgr /ipk W269N-WFGWX-YVC9B-4J6C9-T83GX

5.2 - # slmgr /skms 192.168....

5.3 - # slmgr /ato

5.4 - # slmgr /dlv

Note 1: This is at the oprocs in detail. 

Note 2: I am not the owner of the script file. 

