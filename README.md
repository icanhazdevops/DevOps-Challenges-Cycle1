DevOps-Challenges-Cycle1
========================

Your name:  

Support DevOps Challenges Cycle 1

##Part 1

__Challenge 1__: Write a script that builds a 512MB Cloud Server and returns the root password and IP address for the server. This must be done in PHP with php-opencloud 

__Challenge 2__: Write a script that builds anywhere from 1 to 3 512MB cloud servers (the number is based on user input). Inject an SSH public key into the server for login. Return the IP addresses for the server. The servers should take their name from user input, and add a numerical identifier to the name. For example, if the user inputs "bob", the servers should be named bob1, bob2, etc... This must be done in PHP with php-opencloud. 

__Challenge 3__: Write a script that prints a list of all of the DNS domains on an account. Let the user select a domain from the list and add an "A" record to that domain by entering an IP Address TTL, and requested "A" record text. This must be done in PHP with php-opencloud. 

__Challenge 4__: Write a script that creates a Cloud Files Container. If the container already exists, exit and let the user know. The script should also upload a directory from the local filesystem to the new container, and enable CDN for the new container. The script must return the CDN URL. This must be done in PHP with php-opencloud. 

##Part 2

__Challenge 5__: Write a script that creates a Cloud Database. If a CDB already exists with that name, suggest a new name like "name1" and give the user the choice to proceed or exit. The script should also create X number of Databases and X number of users in the new Cloud Database Instance. The script must return the Cloud DB URL. Choose your language and SDK! 

__Challenge 6__: Write a script that enables and executes a backup for a Cloud Database. Pre-requisite is that the Cloud DB Instance must already exist with a valid database (with some data) and a username with access to the DB. The user executing the script should be able to choose the Instance, Database, and User via the command line arguments to execute the backup. Choose your language and SDK! 

__Challenge 7__: Write a script that creates 2 Cloud Servers and a Cloud Load Balancer. Add the 2 servers Private IP Addresses to the Load Balancer for port 80. For a bonus point, add an Error page served via the Load Balancer for when none of your nodes are available. Choose your language and SDK! 

__Challenge 8__: Write a script that creates a Cloud Performance 1GB Server. The script should then add a DNS "A" record for that server. Create a Cloud Monitoring Check and Alarm for a ping of the public IP address on your new server. Return to the STDOUT the IP Address, FQDN, and Monitoring Entity ID of your new server. Choose your language and SDK! 
