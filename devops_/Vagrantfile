
Vagrant.configure("2") do |config|
 

  config.vm.define "web" do |web|
	  web.vm.box = "ubuntu/bionic64"
      web.vm.network "private_network", ip: "10.10.11.10"
 	  web.vm.provider "virtualbox" do |vb|
      vb.name = "web"
      vb.memory = 1024
      vb.cpus = 1
	end
  end  
  
   config.vm.define "web1" do |web1|
    web1.vm.box = "ubuntu/bionic64"
    web1.vm.network "private_network", ip: "10.10.11.10"
 	web1.vm.provider "virtualbox" do |vb1|
	vb1.name = "web1"
	vb1.memory = 2024
	vb1.cpus = 1
  end
 end  
  
   config.vm.define "web2" do |web2|
    web2.vm.box = "ubuntu/bionic64"
    web2.vm.network "private_network", ip: "10.10.11.10"
 	web2.vm.provider "virtualbox" do |vb2|
	vb2.name = "web2"
	vb2.memory = 1024
	vb2.cpus = 2
  end  
end
end