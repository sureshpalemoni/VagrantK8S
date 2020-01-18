Vagrant.configure("2") do |config|

  config.vm.define "loadb" do |loadb|
    loadb.vm.box = "centos/7"
    loadb.vm.hostname = "loadb"
    loadb.vm.network "private_network", ip: "192.168.56.10"

    loadb.vm.provider "virtualbox" do |loadbm|
      loadbm.memory = 2048
    end
  end

  config.vm.define "master1" do |master1|
    master1.vm.box = "centos/7"
    master1.vm.hostname = "master1"
    master1.vm.network "private_network", ip: "192.168.56.20"

    master1.vm.provider "virtualbox" do |master1m|
      master1m.memory = 2048
      master1m.cpus = 2
    end
  end

  config.vm.define "master2" do |master2|
    master2.vm.box = "centos/7"
    master2.vm.hostname = "master2"
    master2.vm.network "private_network", ip: "192.168.56.30"

    master2.vm.provider "virtualbox" do |master2m|
      master2m.memory = 2048
      master2m.cpus = 2
    end
  end

  config.vm.define "master3" do |master3|
    master3.vm.box = "centos/7"
    master3.vm.hostname = "master3"
    master3.vm.network "private_network", ip: "192.168.56.40"

    master3.vm.provider "virtualbox" do |master3m|
      master3m.memory = 2048
      master3m.cpus = 2
    end
  end
end
