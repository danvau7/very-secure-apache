# very-secure-apache
Extremely Secure Apache HTTP Server configuration files

1. There is not a single place on the web you can find end-to-end Apache HTTP Server configuration. It's very frustrating. 
2. Config assumes Ubuntu 16.04+ and the latest version of Apache. For Apache you usually have to compile from source instead of downloading from the package repos. 
3. Later configs will be added for CentOS7/RHEL
4. Often directives are split up between files such as `httpd.conf` and `security.conf`. I decided to write all of my configs into a single `Apache2.conf` file, which isn't as common anymore, but it makes for easier reading.


NOTE:
Again if you are downloading Apache from the Debian 9 repo, or even the Ubuntu 18.04 LTS repo...you are going to be pretty behind (2.4.25 and 2.4.29 respectively). The latest version of Apache is 2.4.39 and a few of these directives will only work in 2.4.36.
