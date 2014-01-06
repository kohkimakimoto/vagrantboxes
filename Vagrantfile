# -*- mode: ruby -*-
# vi: set ft=ruby :

#
#　Step to create box 
#
# * Add basebox.
#
#        $ vagrant box add centos-6.3-minimal https://dl.dropbox.com/u/7225008/Vagrant/CentOS-6.3-x86_64-minimal.box
#
# * vagrant up
#
#        $ vagrant up
#
# * yum update
#
#        $ yum update
#
# * yum install
#
#        $ yum install -y git
#        $ yum install -y libicu
#        $ yum install -y libxml2-devel
#        $ yum install -y libxslt-devel
#        $ yum install -y openssl

# Vagrantfile API/syntax version. Don't touch unless you know what you're doing!
VAGRANTFILE_API_VERSION = "2"

#
# Vagrant confiugre
#
Vagrant.configure(VAGRANTFILE_API_VERSION) do |config|

  config.vm.box = "centos-6.3-minimal"

  config.vm.provider :virtualbox do |vb|
    vb.gui = true
  end

end