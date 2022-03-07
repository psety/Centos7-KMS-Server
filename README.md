# Centos7-KMS-Server
# **Installation Steps**

1- Download the Centos7 iso.
	2- Install the Centos7. I prefer to install Centos7 with Gnome GUI.

3- Create a root connection and disable the firewall 
	  - $ systemctl stop firewalld
	  - $ systemctl disable firewalld

4 Create an install.sh file and copy the KMSScript into it. 

	- $ cd /home/
	- $ nano install.sh
~~copy the script into it and save it. ~~

	- $ chmod 755 install.sh
	- $ ./install.sh


## Windows Activation 

5 - Open the CMD as administrator

	# slmgr /ipk W269N-WFGWX-YVC9B-4J6C9-T83GX
	# slmgr /skms 192.168....
	# slmgr /ato
	# slmgr /dlv

Note 1: This is at the **oprocs** in detail. 

Note 2: I am **not** the **owner** of the *script* file. 
