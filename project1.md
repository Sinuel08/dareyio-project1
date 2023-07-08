
##WEB STACK IMPLEMENTATION (LAMP STACK) IN AWS

#What is a Technology stack?

A technology stack is a set of frameworks and tools used to develop a software product. This set of frameworks and tools are very specifically chosen to work together in creating a well-functioning software. They are acronymns for individual technologies used together for a specific technology product. some examples are…

LAMP (Linux, Apache, MySQL, PHP or Python, or Perl)
LEMP (Linux, Nginx, MySQL, PHP or Python, or Perl)
MERN (MongoDB, ExpressJS, ReactJS, NodeJS)
MEAN (MongoDB, ExpressJS, AngularJS, NodeJS

##STEP 1 — INSTALLING APACHE AND UPDATING THE FIREWALL

I was able to install apache2 using the command "sudo apt install apcahe 2" but before doing this, i lunched an EC2 instance on AWS and i connected it to my terminal and here is an image of my apache after checking it on browser using the public IP.
![EE92C138-273D-42F2-97F3-712E87E5C755](https://github.com/Sinuel08/dareyio-project1/assets/138252849/60ecfc62-bdc7-4639-8d4c-6014cdb8e55c)

##STEP 2 — INSTALLING MYSQL
I installed MySQL using the command $ sudo apt install mysql-server and get through till i have it secured. Now, i have Apache installed to serve my content and MySQL installed to store and manage my data.

##STEP 3 — INSTALLING PHP
I also have my PHP installed,with the command sudo apt install php libapache2-mod-php php-mysql. This command installs 3 packages at once.
I will need php-mysql, a PHP module that allows PHP to communicate with MySQL-based databases. I'll also need libapache2-mod-php to enable Apache to handle PHP files. Core PHP packages will automatically be installed as dependencies.

##STEP 4 — CREATING A VIRTUAL HOST FOR YOUR WEBSITE USING APACHE
I set up a domain and i called it projectLamp,created a directory for it usingsudo mkdir /var/www/projectlamp and also assigned ownership of it withsudo chown -R $USER:$USER /var/www/projectlamp

##STEP 5 — ENABLE PHP ON THE WEBSITE
after enabling, i got this image on my website
