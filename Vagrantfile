Vagrant.configure("2") do |config|

  config.vm.box = "hashicorp-vagrant/ubuntu-16.04"
  config.vm.network "forwarded_port", guest: 80, host: 8080
  config.vm.network "forwarded_port", guest: 443, host: 8443
end
