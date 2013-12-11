Vagrant.configure("1") do |config|
  config.vm.box = "debian-7.2.0-amd64"
  config.vm.network :forwarded_port, guest: 80, host: 8080
  config.vm.synced_folder ".", "/opt"
end
