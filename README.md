# Raspi-Control
A Node.js app that let's you control your Raspberry Pi remotely

#Installation guide
Copy the files to a directory on your Raspberry Pi:
```
git clone https://github.com/Lisamith/Raspi-Control.git
```

Edit the top of the index.js file so that it fits to your configuration:
```
var host = 'IPOFTHERASPBERRY',
	port = SSHPORT,
	user = 'USERNAME',
	password = 'PASSWORD';
```

Execute the following:
```
cd Raspi-Control
npm install
node index.js
```

You should now be able to access the control panel via
another computer on the network
```
IPoftheRaspberry:2000
```
