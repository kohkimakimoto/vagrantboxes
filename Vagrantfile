# -*- mode: ruby -*-
# vi: set ft=ruby :

#
#　Usage: Step to create my custom box.
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
#
# * vagrant package
#
#        $ vagrant package

# Vagrantfile API/syntax version. Don't touch unless you know what you're doing!
VAGRANTFILE_API_VERSION = "2"

#
# Vagrant confiugre
#
Vagrant.configure(VAGRANTFILE_API_VERSION) do |config|

  config.vm.box = "centos-7.0"

  config.vm.provider :virtualbox do |vb|
    vb.gui = false
  end

end
