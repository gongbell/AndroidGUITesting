# -*- mode: ruby -*-
# vi: set ft=ruby sw=2 ts=2 :

# Vagrant Box for Android Test Input Generation Tools
# Author: Shauvik Roy Choudhary (http://shauvik.com)
# Last Modified Date: 01/23/2015

Vagrant.configure("2") do |config|
#    config.vm.box = "androtest"
#    config.vm.box = "androidzyy"
    config.vm.box = "androqrs"
    # TODO: offer premade images for download
    config.vm.box_url = ""

  config.vm.provider :virtualbox do |vb|
    vb.memory = 6144 #8192 #65535 #6144
    vb.cpus = 2
    vb.customize ["modifyvm", :id, "--vrde", "on"]
    vb.customize ["modifyvm", :id, "--vrdeaddress", "0.0.0.0"]
    vb.customize ["modifyvm", :id, "--vrdeport", "5000-5025"]
  end

  # Run bootstrap script
  # config.vm.provision "shell", path: "bootstrap.sh"

  config.vm.define "run1" do |r|
    r.vm.hostname="run1"
  end 
  config.vm.define "run2" do |r|
    r.vm.hostname="run2"
  end
  config.vm.define "run3" do |r|
    r.vm.hostname="run3"
  end
  config.vm.define "run4" do |r|
    r.vm.hostname="run4"
  end
  config.vm.define "run5" do |r|
    r.vm.hostname="run5"
  end
  config.vm.define "run6" do |r|
    r.vm.hostname="run6"
  end
  config.vm.define "run7" do |r|
    r.vm.hostname="run7"
  end
  config.vm.define "run8" do |r|
    r.vm.hostname="run8"
  end
  config.vm.define "run9" do |r|
    r.vm.hostname="run9"
  end
  config.vm.define "run10" do |r|
    r.vm.hostname="run10"
  end
end
