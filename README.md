## Update JSFMT Packages
### Install related packages

```
cd ~/Library/Application\ Support/Sublime\ Text\ 3/Packages/jsfmt
npm install esformatter-quotes esformatter-braces esformatter-dot-notation esformatter-remove-trailing-commas esformatter-jsx --save
```

### (Optional) Make sure your're using latest Node.js

```
brew install node
brew update
brew upgrade
```

### Switch to system Node.js and install eslint related packages

```
nvm use system
npm install eslint eslint-plugin-react eslint-plugin-react-native -g
```
