# install-scripts
May contain taste of Arch Linux

These script configure or install packages.

Designed for Arch Linux installation speedup but could work on other distributions too.

## Usage
Files can be executed and will first show usages, prerequisites and hints about modifications they're doing.

## File naming scheme
### *.user
Execute as non root user. May be used for root as user himself as well. Script may warn you if you're doing wrong.  
`bash script.user` or `./script.user`

### *.usersudo
Execute as user with sudo permission. Script may prepare some things in user space and will execute parts as root with sudo.  
`bash script.usersudo` or `./script.usersudo`

### *.root
Execute by root himself or sudo. This script will definately work in systems paths.  
- As user with sudo: `sudo bash script.root` or `sudo ./script.root`
- As root directly: `bash script.root` or `./script.root`
