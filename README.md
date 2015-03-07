# vagrantBerksMammoth
Vagrant using berkshelf for meanMammoth

#### Prerequisites
* Install [vagrant](https://www.vagrantup.com/downloads.html).
* Install [chef-dk](https://downloads.chef.io/chef-dk/).
* Add opscode/chefdk/bin to your system PATH. Check [this](http://berkshelf.com/).
* Create meanMammoth folder or [clone it](https://github.com/daxsorbito/meanMammoth.git). 

_Note: vagrantBerksMammoth and meanMammoth should be on the same folder level_

#### Set-up
* git clone https://github.com/daxsorbito/vagrantBerksMammoth.git
* cd vagrantBerskMammoth
* berks vendor cookbooks/

#### Running
* vagrant up
