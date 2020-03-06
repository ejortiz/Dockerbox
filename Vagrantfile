Vagrant.configure("2") do |config|
  config.vm.box = "elegoev/ubuntu-18.04-docker"
  config.vm.network "forwarded_port", guest: 80, host: 8080
  config.vm.synced_folder "./docker", "/home/vagrant"
  
  config.vm.synced_folder "./mainsite", "/var/lib/docker/volumes/djanaconda-container_mainsite/_data", disabled:false, type: "virtualbox",  owner: "vagrant", group: "www-data", mount_options:["dmode=775,fmode=664"]

end
