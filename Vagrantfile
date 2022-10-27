
Vagrant.configure("2") do |config|
 
  config.vm.box = "ubuntu/focal64"

  config.vm.define:Desafio01

  config.vm.network "forwarded_port", guest: 80, host: 8090

  config.vm.network "public_network", ip: "192.168.100.127"

  config.vm.provision "shell",
  path:"script.sh"

end
