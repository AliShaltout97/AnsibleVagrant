# AnsibleVagrant
This is a sample project that uses pre-deployed Vagrant VMs to show Ansbile multiple functionalities as below:  <br />
1- Used Inventory file to define all the hosts and grouped them accordingly.  <br />
2- Used Roles functionality and by creating the galaxy and defined variables, hanlders and tasks.  <br />
3- Used loops and conditions inside the main tasks file to install several services based on the OS.  <br />
4- Enabled NTP Service, created a group and added a list of users into that group.  <br />
5- Used the copy content module to create the motd.  <br />
6- Deployed NTP configuration file using template module based on the OS, then notified handler to restart the NTP service.  <br />
7- Used file module to create a directory with specific permissions and copied a file locally to the corresponding directories.
