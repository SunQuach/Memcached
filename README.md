# Memcached
Instructions for installing "Memcached on OS Windows"

Steps to install Memcached on Windows:

  1. Download file memcached by ULR: https://github.com/SunQuach/Memcached
  
  2. Unzip it in some hard drive folder. For example ***C:\memcached***
  
  3. There will be memcached.exe file in the unzipped folder.
  
  4. Open a command prompt (need to be opened as administrator). Run command line:
  
  	c:\memcached\memcached.exe -d install
  
  5. If the installation is successful, you can start the Memcached service with the command:
  
  	net start memcached
  
  6. For start and stop run following command line
  
  	c:\memcached\memcached.exe -d start
	c:\memcached\memcached.exe -d stop
