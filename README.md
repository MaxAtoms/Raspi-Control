# Raspi-Control
A Node.js app that let's you control your Raspberry Pi remotely

#Installation guide
Copy the files to a directory on your Raspberry Pi:
```

```

Edit the login.js file so that it fits to your configuration:
```
var host = 'IPOFTHERASPBERRY',
	port = SSHPORT,
	user = 'USERNAME',
	password = 'PASSWORD';
```

Execute the following:
```
cd your/directory
npm install
node index.js
```

You should now be able to access the control panel via
another computer on the network
```
IPoftheRaspberry:2000
```
