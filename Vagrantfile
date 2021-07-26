VAGRANTFILE_API_VERSION = "2"

Vagrant.configure(VAGRANTFILE_API_VERSION) do |config|
  config.ssh.insert_key = false  
  config.vm.box = "ubuntu/trusty64"
  config.vm.network :public_network, ip:"192.168.1.150"
end
