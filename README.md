# Menu_Item_Catalog Project
This project is about creating restaurant menu website which can allow us to add,edit,delete restaurants and its menu items.
### Before starting our project we need to download some softwares
1. Virtual Box
2. Vagrant
### Vagrant
Vagrant provides the same, easy workflow regardless of your role as a developer, operator, or designer. It leverages a declarative configuration file which describes all your software requirements, packages, operating system configuration, users, and more.

Heres a link to downlaod [vagrant](https://www.vagrantup.com/)

### Virtual Box
  Download the [Virtual Box](https://www.virtualbox.org/) from this link
  
### After downloading both vagrant and virtual box
1. Clone the fullstack-nanodegree-vm
2. Open a terminal and change your directory to /FSND-Virtual-Machine/vagrant.
3. And start using these commands
    * vagrant up(This will downlaod the desired os image and install it the downlaod will be taken place once and after that this command will always be used to open the virtual box)
    * vagrant ssh (This will start our virtual machine)
 4. Make sure on changing the directory to /vagrant(The place in which the files can be accesed by both host and virtual machine)
 5. After that create your own folder for the project i created 'menu_item' and change the directory to it.
 ## How to do this project
 1. Create a database using sql alchemy and save it as **databasesetup.py** and run it.
 2. After that push data into the database using **lotsofmenus.py**.
 3. Create **static** and **template** folder to store css and html files which we can use in our program.
 4. Create a file **project.py** and the code which describes how our application works.
 5. After exceuting **python project.py** we can access the restaurant menu application at **localhost:5000/**.
 6. That's how we created and use the menu app.