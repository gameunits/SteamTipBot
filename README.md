Gameunits SteamTipBot
=================

Tip Gamers on Steam with Gameunits!

If you have been invited to join the group by our tippingbot, someone tipped you! 
Join the group chat room to accept your tip!

To send the bot commands, open up the group chat and double click on our tippingbot's name (with the golden star) in the sidebar to send a private message. Send "+register" to register yourself with the bot, receive a deposit address and start tipping!

Commands:
```
+register - Notify the bot that you exist. You will receive a deposit address that is locked to your account.
+deposit - Display deposit address
+balance - Check the amount of Gameunits in your wallet.
+history - Display your current balance and a list of your 10 most recent transactions
+withdraw Gamerscoins - Withdraw funds in your account to the specified address
+tip Gameunits (+verify) - Send a Steam user a tip. People who aren't registered with the bot will be sent a friend request. 
If +verify is added, the bot will send a message confirming the tip to the group chat. More information at the bot's website.
+version - Current bot version
+help - Help dialog with these commands
```    
	
All Contributors are Welcome!!!

Installing TipBot on Linux :

```
//How to Install MongoDB 2.6 on Ubuntu and Dabian Systems
sudo apt-key adv --keyserver hkp://keyserver.ubuntu.com:80 --recv 7F0CEB10

For Ubuntu:
echo 'deb http://downloads-distro.mongodb.org/repo/ubuntu-upstart dist 10gen' | sudo tee /etc/apt/sources.list.d/mongodb.list

For Debian:
echo 'deb http://downloads-distro.mongodb.org/repo/debian-sysvinit dist 10gen' | sudo tee /etc/apt/sources.list.d/mongodb.list

sudo apt-get update
sudo apt-get install mongodb-org

//If you want to install any specific version of MontoDB, define the version number like below
apt-get install mongodb-org=2.6.0 mongodb-org-server=2.6.0 mongodb-org-shell=2.6.0 mongodb-org-mongos=2.6.0 mongodb-org-tools=2.6.0

//Start/Stop MongoDB Service:
sudo service mongod start
sudo service mongod stop

//Install tsc compiler
sudo npm install typescript -g

//Add user for TipBot
adduser Tipbot
su Tipbot

//Start mongod :
mongod

//Clone the Project and compile the Tipbot
npm install
tsc bot.ts --module "commonjs"

//Run TipBot
node bot.js
```
	