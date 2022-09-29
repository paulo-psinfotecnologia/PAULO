Vagrant.configure("2") do |config|

# Configurando a VM
    config.vm.define:psinfo do |psinfo_config|
        psinfo_config.vm.box = "centos/7"
        psinfo_config.vm.network "public_network"
        psinfo_config.vm.provider:virtualbox do |vb|
            vb.name = "psinfotecnologia"
            vb.memory = "1024"
            vb.cpus = "2"
        end
    end
end