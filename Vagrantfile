Vagrant.configure("2") do |box|
  box.vm.box = "peru/ubuntu-20.04-server-amd64"
  box.vm.box_version = "20210222.01"
  box.vm.network "private_network", ip: "192.168.111.111"
  box.vm.provision "shell", inline: <<-SHELL
	      apt-get install python3
  	  SHELL
  end

