Vagrant.configure("2") do |config|


  config.vm.define "devops" do |devops|
    devops.vm.box = "ubuntu/xenial64"
        devops.vm.network "private_network", ip: "192.168.33.150"
	devops.vm.hostname = "devops.r9it.com.br" 
       config.vm.provider "virtualbox" do |vb|
        vb.memory = "1024"
        end



        end

  config.vm.define "server" do |server|
    server.vm.box = "ubuntu/xenial64"
        server.vm.network "private_network", ip: "192.168.33.151"
	server.vm.hostname = "server.r9it.com.br" 
       config.vm.provider "virtualbox" do |vb|
        vb.memory = "1024"
        end



        end

 config.vm.define "exercicio" do |exercicio|
    exercicio.vm.box = "centos/7"
        exercicio.vm.network "private_network", ip: "192.168.33.152"
	exercicio.vm.hostname = "exercicio.r9it.com.br" 
       config.vm.provider "virtualbox" do |vb|
        vb.memory = "1024"
        end



        end


end 
