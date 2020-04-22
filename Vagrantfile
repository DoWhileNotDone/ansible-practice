Vagrant.configure("2") do |config|
  config.vm.provision "shell", inline: "echo Hello"

  config.vm.define "ubuntu16" do |ubuntu16|
    ubuntu16.vm.box = "bento/ubuntu-16.04"
    ubuntu16.vm.network "private_network", ip: "192.168.50.52"
  end

  config.vm.define "ubuntu18" do |ubuntu18|
    ubuntu18.vm.box = "bento/ubuntu-18.04"
    ubuntu18.vm.network "private_network", ip: "192.168.50.53"
  end

  config.vm.define "centos7" do |centos7|
    centos7.vm.box = "centos/7"
    centos7.vm.network "private_network", ip: "192.168.50.54"
  end

  config.vm.define "centos8" do |centos8|
    centos8.vm.box = "centos/8"
    centos8.vm.network "private_network", ip: "192.168.50.55"
  end


end
