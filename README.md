# Getting started
- Our NodeJS App is dependent on v18.20.8, you need to install the similar version
- TCP Port 3000 is enabled in Security Group 

### Install NodeJS on EC2 Ubuntu instance
```jsx
# Be root user for all installation
sudo su

# Download and install nvm:
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.40.3/install.sh | bash

# in lieu of restarting the shell
\. "$HOME/.nvm/nvm.sh"

# Download and install Node.js:
nvm install 18

# Install yarn
apt install cmdtest
```

### To install NodeJS on Windows / MacOS / Linux Distribution 
URL --> https://nodejs.org/en/download

### Verify the Node.js & npm version:
```jsx
node -v # Should print "v18.20.8".
nvm current # Should print "v18.20.8".
npm -v # Should print "10.8.2".
```

### Steps to deploy Locally or on DEV environment
1. Clone the app
```jsx
git clone https://github.com/amigo-nishant/getting-started.git
```

2. Clone the app
```jsx
git clone https://github.com/amigo-nishant/getting-started.git
```

3. Clone the app
```jsx
git clone https://github.com/amigo-nishant/getting-started.git
```

4. Change the directory
```jsx
cd getting-started
```

5. Deploy the App
```jsx
npm install
node src/index.js
```

6. Test the App Frontend
```jsx
http://pblic-ip-ec2:3000/
```
