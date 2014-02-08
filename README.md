Yito Development
================

Recomended structure

yito
  yito_base
  yito_plugins
  yito_utils

Dependencies
------------

RVM and NPM are necesary in order to build

rvm

\curl -L https://get.rvm.io | bash -s stable --ruby

Ruby 1.9.2 is necesary because picasa gem does not work on Ruby 2.0

npm (node.js)

Creating the folders and download the projects
----------------------------------------------

mkdir yito
cd yito
mkdir yito_base
mkdir yito_plugins
mkdir yito_utils

Prepare gemset and install bundle
---------------------------------

rvm use 1.9.2
rvm gemset create yito
gem install bundle

And then every time
rvm use 1.9.2@yito


Yito Base
---------

Copy scripts/yito.sh in a folder where you want to download the yito core system and execute the script

  ./yito.sh 

Yito Plugins
------------

Copy scripts/yito_plugins.sh in a folder where you want to download the plugins and execute the script

  ./yito_plugins.sh
 
