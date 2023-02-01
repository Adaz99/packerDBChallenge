# PackerDB Challenge

Within this project, I configured a Packer.json file to ensure that i was able to create a Amazon Machine Image (AMI) on Amazon Web Services (AWS). Once the image was built, I launched an AWS instance, and with the SSH command (ssh -i "airidas-awskey.pem" ubuntu3.17.187.83) I was able to access the virtual machine through the terminal. To ensure the mongodb was fully functional, I ran the 'mongosh' command, which allowed access to the database. To ensure that everything was working, I executed the 'show dbs' command to list the available databases. The outcome of this project is a functional virtual machine with an active MongoDB service.



The gif below shows:
-  The packer.json configuration working and setting up the ami
-  The instance working and running on AWS
-  Being able to SSH into the VM and able to connect to Mongdb and see the dbs available 
![demo](./Recording%202023-01-31%20at%2015.28.52.gif)
