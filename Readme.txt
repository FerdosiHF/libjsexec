Libjsexec
This library is used for allowing Javascript files to directly perform system calls within the host system. I have created this library within my graduation project as javascript prohibits this type of calls due to security issues. With this library, it is possible to call system binaries and pass any types and number of options to it securely by digitally signing each binary file.

Installation procedures:
	1- Copy jsexec to /usr/sbin and make sure of its excutable permission.
	2- Copy libjsexec.conf to /etc/init.
	3- Copy libjsexec to /etc/init.d.
	4- Excute the following command: sudo update-rc.d libjsexec defaults.
	5- verify the installation by monitoring system log.

Note:
This library is not maintained and became so deprecated. For any help, contact:hfferdosi89@gmail.com

