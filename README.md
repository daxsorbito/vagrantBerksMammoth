# vagrantMammoth
Vagrant for meanMammoth

#Pre-requisites
>Install [vagrant](https://www.vagrantup.com/downloads.html).
>Install [chef-dk](https://downloads.chef.io/chef-dk/).
>Add opscode/chefdk/bin to your system PATH. Check [this](http://berkshelf.com/).

## Set-up
Use **--recursive** option of **git clone** when cloning this repo so that the submodules would also be initialized
>git clone https://github.com/daxsorbito/vagrantBerksMammoth.git
>cd vagrantBerskMammoth
>berks vendor cookbooks/

## Running
>vagrant up
