# Terra Station Wallet extension

![Banner](Banner.png)

**Terra Station Wallet extension** is a browser extension to interact with [Terra Core](https://github.com/terra-money/core).

Terra Station Wallet extension allows users to:

- View the balances and values of coins and tokens held in the connected wallet.
- View a list of transactions signed by the connected wallet.
- Send tokens to another Terra wallet.
- Swap currencies on the Terra network at the effective exchange rate.

## Install nodejs version 16 in ubuntu 20.04

This command will add PPA sources required to be able to install NodeJS 16 on your Ubuntu 20.04 installation
```
curl -s https://deb.nodesource.com/setup_16.x | sudo bash
```
Now that the PPA source has been added, we can install NodeJS 16 on our Ubuntu 20.04 installation. Run the following command:
```
sudo apt install nodejs -y
```
Finally, let's confirm the installed version. Run the following command:
```
node -v
```


## Building Terra Station Wallet extension

This project was bootstrapped with [Create React App](https://create-react-app.dev/).

Build Terra Station Wallet extension with the following commands:

```
git clone https://github.com/terra-money/station-extension.git
cd station-extension
npm i
npm run build
```

Builds the extension.
Open `/build` to view it.

for Static Server
For environments using Node, the easiest way to handle this would be to install serve and let it handle the rest:
```
npm install -g serve
serve -s build
```
The last command shown above will serve your static site on the port 3000. Like many of serve’s internal settings, the port can be adjusted using the -l or --listen flags:
```
serve -s build -l 4000
```
Run this command to get a full list of the options available:
```
serve -h
```


> Note: For the Windows operating system, separate the paths by semicolons in the `.env` file.
