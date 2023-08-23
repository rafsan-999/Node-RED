## Node-RED
Node-RED is a programming tool for wiring together hardware devices, APIs and online services in new and interesting ways.
It provides a browser-based editor that makes it easy to wire together flows using the wide range of nodes in the palette 
that can be deployed to its runtime in a single-click

### Official Documetation Link: 
https://nodered.org/docs/getting-started/local

## How to Install Node-RED on linux:
##### Prerequisites
This script will work on any: 
* Debian-based operating system 
* Ubuntu and Diet-Pi.
* Raspberry Pi 
* To install Node-RED locally you will need a supported version of Node.js 18.x.
* You need to install Node.JS version 18.x and NPM installed on your server.
* For Snap installation you need to install Snap on your server.

# Installing with snap
    sudo snap install node-red
# Installing with npm
    sudo npm install -g --unsafe-perm node-red
# Running
Once installed as a global module you can use the node-red command to start Node-RED in your terminal. 
You can use Ctrl-C or close the terminal window to stop Node-RED.

    node-red
    
### After successfully Install Node-Red you will find this Massage:

    Welcome to Node-RED
    ===================
    
    30 Jun 23:43:39 - [info] Node-RED version: v1.3.5
    30 Jun 23:43:39 - [info] Node.js  version: v14.7.2
    30 Jun 23:43:39 - [info] Darwin 19.6.0 x64 LE
    30 Jun 23:43:39 - [info] Loading palette nodes
    30 Jun 23:43:44 - [warn] rpi-gpio : Raspberry Pi specific node set inactive
    30 Jun 23:43:44 - [info] Settings file  : /Users/nol/.node-red/settings.js
    30 Jun 23:43:44 - [info] HTTP Static    : /Users/nol/node-red/web
    30 Jun 23:43:44 - [info] Context store  : 'default' [module=localfilesystem]
    30 Jun 23:43:44 - [info] User directory : /Users/nol/.node-red
    30 Jun 23:43:44 - [warn] Projects disabled : set editorTheme.projects.enabled=true to enable
    30 Jun 23:43:44 - [info] Creating new flows file : flows_noltop.json
    30 Jun 23:43:44 - [info] Starting flows
    30 Jun 23:43:44 - [info] Started flows
    30 Jun 23:43:44 - [info] Server now running at http://127.0.0.1:1880/red/

#### Running Node-RED on your web browser at http://127.0.0.1:1880
