# ubuntu-post-install

This script provides a bootstrapping script for Ubuntu 16.04.

### Usage
To install the base configuration just run

    git clone https://github.com/uloco/ubuntu-post-install.git
    cd ubuntu-post-install
    source index
    post-install

### Options

Only one option at a time is allowed at the moment
e.g. post-install --proxy && post-install --base

`--proxy` install proxy settings (cntlm)
`--base` base installation
`--advanced` advanced installation (git config, themeing, extend keyboard)
`--optional` optional installation
`--kernel` install latest available kernel from official ubuntu repos
