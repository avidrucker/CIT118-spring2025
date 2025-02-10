# How to Install LCC.js on Mac/Linux

- install node
- git should be installed already
- clone lccjs from GitHub and run it

## Install node

1. Open Terminal and run the following commands (you can copy them directly from https://nodejs.org/en/download)

    a. `curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.40.1/install.sh | bash` (this will install nvm)  
    b. `nvm install 22` (this will install node version 22)  
    c. `node -v` (this should print "v22.13.1".)

## Clone lccjs from GitHub

2. Via the Terminal run the following commands:

    a. `cd ~/Documents` (this navigates to your Documents folder)  
    b. `git clone https://github.com/avidrucker/lccjs.git` (this will download lccjs to your Documents folder)  
    c. `cd lccjs` (this navigates to the lccjs folder)  
    d. `node ./src/core/lcc.js ./demos/demoA.a` to see if you can run the first demo (it should ask you to type your name and then hit Enter, and then print out the number 5)