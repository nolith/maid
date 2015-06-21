# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure(2) do |config|
  config.vm.box = "ubuntu/trusty64"

  # config.vm.provider "virtualbox" do |vb|
  #   vb.gui = false
  #   vb.memory = "1024"
  # end

  config.vm.synced_folder ".", "/opt/maid"
  # config.vm.provision "shell", inline: <<-SHELL
  #   sudo apt-get update
  #   #sudo apt-get install -y xfce4 virtualbox-guest-dkms virtualbox-guest-utils virtualbox-guest-x11
  #   #sudo VBoxClient-all
  #   sudo apt-get install -y python-dev python-pip
  #   sudo pip install ansible
  # SHELL

  config.ssh.forward_agent = true
end
