# Project-4 MEAN STACK IMPLEMENTATION

### update and upgrade ubuntu

`sudo apt update`

`sudo apt upgrade`

### add certificate

`sudo apt -y install curl dirmngr apt-transport-https lsb-release ca-certificates`

### install nodejs

`curl -sL https://deb.nodesource.com/setup_14.x | sudo -E bash -`
![node-source](/images/node-source.jpg)

`sudo apt install -y nodejs`
![nodejs installation](/images/nodejs-install.jpg)

### install mongoDB

`sudo apt-key adv --keyserver hkp://keyserver.ubuntu.com:80 --recv 0C49F3730359A14518585931BC711F9BA15703C6`

`echo "deb [ arch=amd64 ] https://repo.mongodb.org/apt/ubuntu trusty/mongodb-org/3.4 multiverse" | sudo tee /etc/apt/sources.list.d/mongodb-org-3.4.list`

`sudo apt install -y mongodb`

`sudo service mongodb start`
![mongodb](/images/mondo-install.jpg)

`mkdir Books && cd Books`

`npm init`

`sudo npm install body-parser`
![npm-init and body-parser install](/images/npm-body-parser.jpg)

`vi server.js`

### install express and set up routes to the server

`sudo npm install express mongoose`

![mongoose install](/images/mongoose-install.jpg)

`mkdir apps && cd apps`

`vi routes.js`

`mkdir models && cd models`

`vi book.js`

`mkdir public && cd public`

`vi script.js`

`vi index.html`

`node server.js`
![start node server](/images/start%20node%20server.jpg)
