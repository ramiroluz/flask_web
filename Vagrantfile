Vagrant.require_version ">= 1.7.0"

Vagrant.configure(2) do |config|
    config.vm.box = "debian/jessie64"
    config.ssh.insert_key = false
    config.vm.network "forwarded_port", guest: 5000, host: 5000

    config.vm.provision "ansible" do |ansible|
        ansible.verbose = "v"
        ansible.playbook = "playbook.yml"
    end
end
