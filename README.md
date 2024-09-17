# sonosdeck
Control Sonos over Streamdeck.

To install this software you basically need to install "node.js" --> 
Win:   https://nodejs.org/dist/v16.15.0/node-v16.15.0-x64.msi
Mac:   https://nodejs.org/dist/v16.15.0/node-v16.15.0.pkg
Linux: https://nodejs.org/dist/v16.15.0/node-v16.15.0.tar.gz

After you install "node.js" you basically have to install "npm" library -->
Win: 
Open PowerShell with Adminrights and write npm install -g npm
Installed!

Download all files as a .zip from branch "recommended-files" 
Extract the .zip file in your prefered location. 
Open a PowerShell Window in this location. (Shift + Right Click)
Write npm install --production in this PowerShell Window and hit ENTER
After this simply write npm start (also in this PowerShell Window), the Server will start. 

Now you can control your system by invoking the following commands:

http://localhost:5005/zones
http://localhost:5005/lockvolumes
http://localhost:5005/unlockvolumes
http://localhost:5005/pauseall[/{timeout in minutes}]
http://localhost:5005/resumeall[/{timeout in minutes}]
http://localhost:5005/preset/{JSON preset}
http://localhost:5005/preset/{predefined preset name}
http://localhost:5005/reindex
http://localhost:5005/{room name}/sleep/{timeout in seconds or "off"}
http://localhost:5005/{room name}/sleep/{timeout in seconds or "off"}
http://localhost:5005/{room name}/{action}[/{parameter}]
