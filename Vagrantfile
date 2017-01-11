Vagrant.configure("2") do |config|
  config.vm.provision "shell", inline: "echo Running"

  config.vm.define "mongo1" do |mongo1|
    mongo1.vm.box = "hashicorp/precise64"
mongo1.vm.network "public_network"
mongo1.vm.provision :shell, path: "mongo.sh"
  end

  config.vm.define "mongo2" do |mongo2|
    mongo2.vm.box = "hashicorp/precise64"
mongo2.vm.network "public_network"
mongo2.vm.provision :shell, path: "mongo.sh"
  end

  config.vm.define "mongo3" do |mongo3|
    mongo3.vm.box = "hashicorp/precise64"
mongo3.vm.network "public_network"
mongo3.vm.provision :shell, path: "mongo.sh"
  end

  config.vm.define "mongo4" do |mongo4|
   mongo4.vm.box = "hashicorp/precise64"
mongo4.vm.network "public_network"
mongo4.vm.provision :shell, path: "mongo.sh"
  end
end