### Install and configure Apache

With this bash file, we can install and configure some parameters. For this, first we make a update and the and upgrade. After that, we make the insallation of the Apache.

### For install Apache2 in Linux (RPI):

1) sudo apt update
2) sudo apt upgrade
3) sudo apt install apache2 -y

### For write:

1) cd /var/www/hmtl
2) sudo mv index.html old_index.hmtl
3) sudo nano index.hmtl

When you in to the index.html, you can edit this file like:

<h1> Hi, iam <h1>

### For activate the server:

1) service apache2 status
2) service apache2 start
3) service apache2 stop
4) service apache2 restart
