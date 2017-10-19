Example templates for Vagrant and Packer.
# Intro
There are already some existing GitHub projects providing templates to create machines with Packer. However I created this project for learning purposes . In addition to the packer documentation I also took some inspiration from these great projects:
* https://github.com/kaorimatz/packer-templates
* https://github.com/mwrock/packer-templates
* https://github.com/MattHodge/PackerTemplates
* https://github.com/jacqinthebox/packer-templates

# Structure
+ [images](https://github.com/papanito/packer-vagrant/tree/master/images) - images for better illustration in the README.txt
+ [packerfiles](https://github.com/papanito/packer-vagrant/tree/master/packerfiles) - json and cfg (variables) for packera
  + [iso](https://github.com/papanito/packer-vagrant/tree/master/packerfiles/iso) - os specific variables like iso name and checksum
  + [scripts](https://github.com/papanito/packer-vagrant/tree/master/packerfiles/scripts) - scripts for provisioning machines with packer
+ [scripts](https://github.com/papanito/packer-vagrant/tree/master/scripts) - script to be used for provisioning
+ [unattended](https://github.com/papanito/packer-vagrant/tree/master/unattended) - preseed files for Linux and Autounattend files for Windows
  + [windows](https://github.com/papanito/packer-vagrant/tree/master/unattended/windows) - autounattended files for Windows
    + 10         - Windows 10
    + ...
  + [linux](https://github.com/papanito/packer-vagrant/tree/master/unattended/linux) - answer files for Linux
    + Ubuntu     - Ubuntu specific files
    + ...
+ [vagrantfiles](https://github.com/papanito/packer-vagrant/tree/master/vagrantfiles)
  + <os version> - 

Additional information can be found in the related subfolders