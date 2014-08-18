rails-vagrant-toybox
====================

# rails-vagrant-toybox

The intent of this project is to create a turnkey rails configuration that incorporates best tools and practices. It includes a Vagrant box provisioned with Postgresql and other useful tools, and a Rails project outfitted with best practice tools like rspec and bootstrap. 

## Usage

vagrant up

vagrant ssh

cd /vagrant

bundle install

## Design decisions

### Why not rvm?

Of course, rvm is a useful tool for development. But this is meant to be the basis of a production system. For that, you should use a direct ruby install. In this case, it's Ruby 2.1.2. 

