Vagrant.configure("2") do |config|
  config.vm.box = "bento/ubuntu-22.04"
  config.vm.box_version = "202508.03.0"
  config.vm.network "forwarded_port", guest: 3001, host: 3001, host_ip: "127.0.0.1"
  config.vm.network "public_network", type: "dhcp"

  config.vm.provider "virtualbox" do |vb|
     vb.name = "Uptime Kuma"
     vb.gui = true
     vb.memory = "1024"
     vb.cpus = 1
  end

  config.vm.provision "shell", path: "setup.sh"
  end
