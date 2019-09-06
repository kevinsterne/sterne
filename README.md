# sterne
A site for Kevin Sterne


### Requirements
- Node.js
- NPM
- PM2
----
- Text Editor
- FTP software
- Terminal

### Instructions

##### To restart server
1. go to www.digitalocean.com and login
2. access the IAintAfraidOfNoGhosts group
3. Select the fueledbylefawn droplet (This is where all of the website files live)
4. Select "access" and launch console (login credentials will be provided to you outside of this Read Me.
5. Run command `sudo reboot`

NOTE: running this command will require you to restart pm2.

##### To restart PM2
1. go to www.digitalocean.com and login
2. access the IAintAfraidOfNoGhosts group
3. Select the fueledbylefawn droplet (This is where all of the website files live)
4. Select "access" and launch console (login credentials will be provided to you outside of this Read Me.
5. run command `pm2 list` to see what is running. The file that runs is called index.js.
6. See http://pm2.keymetrics.io/docs/usage/pm2-doc-single-page/ for other commands (star, stop, etc).

##### Editing files
* Requires SFTP setup into server(fileZilla).
* After files are changed on your computer they must be transferred to the server via SFTP
* PM2 must be restarted after files are added or edited on the server
