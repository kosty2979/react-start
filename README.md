install nodejs :

    sudo apt-get update
    sudo apt-get install nodejs




or install nvm( "Node.js version manager" ):


    curl -sL https://raw.githubusercontent.com/creationix/nvm/v0.31.0/install.sh -o install_nvm.sh

bash install_nvm.sh

check version node:
nvm ls-remote

and install node-version:

nvm install 6.9.4

Create a symbolic link for node, as many Node.js tools use this name to execute.

 sudo ln -s /usr/bin/nodejs /usr/bin/node 

 Then install the Node package manager, npm:

  sudo apt-get install npm 