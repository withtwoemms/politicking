Vagrant.configure("2") do |politicking|
  politicking.vm.box = "ubuntu/trusty64"
  politicking.vm.network "forwarded_port", host: 8080, guest: 80
  politicking.vm.synced_folder "./", "/vagrant"
end
