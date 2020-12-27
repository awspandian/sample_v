	Vagrant.configure("2") do |config|
	config.vm.define "ansible" do |ansible|
    ansible.vm.box = "centos/7"
	ansible.vm.hostname = "ansible"
    ansible.vm.network "private_network", ip: "192.168.33.100"
	end
    config.vm.define "sr1" do |sr1|
    sr1.vm.box = "centos/7"
	sr1.vm.hostname = "sr1"
    sr1.vm.network "private_network", ip: "192.168.33.101"
	end
    config.vm.define "sr2" do |sr2|
    sr2.vm.box = "centos/7"
	sr2.vm.hostname = "sr2"
    sr2.vm.network "private_network", ip: "192.168.33.102"
	end
    config.vm.define "sr3" do |sr3|
    sr3.vm.box = "ubuntu/bionic64"
	sr3.vm.hostname = "sr3"
    sr3.vm.network "private_network", ip: "192.168.33.103"
	end
	config.vm.define "sr4" do |sr4|
    sr4.vm.box = "ubuntu/bionic64"
	sr4.vm.hostname = "sr4"
    sr4.vm.network "private_network", ip: "192.168.33.104"
	end
end