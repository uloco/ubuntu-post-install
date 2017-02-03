# ubuntu-post-install

This script provides a bootstrapping script for Ubuntu 16.04.

### Usage
To install the base configuration just run

    git clone https://github.com/uloco/ubuntu-post-install.git
    cd ubuntu-post-install
    ./index [option]

### Options

Only one option at a time is allowed at the moment  
e.g. `./index --proxy && ./index --base`


`--proxy` install proxy settings (cntlm)  
`--base` base installation  
`--advanced` advanced installation (git config, themeing, extend keyboard)  
`--optional` optional installation  
`--kernel` install latest available kernel (be cautious, this could break your system)
