Vagrant.configure(2) do |config|
 config.vm.box = "centos/7"
 config.vm.hostname = "centos.exmaple.com" 
 config.vm.provision "ansible" do | ansible |
  ansible.playbook = 'playbook.yml'
 end
end

