### error
When trying to install a module or build an app, I got 'npm ERR! Cannot read property 'match' of undefined' on console.

### fix
Remove package-lock.json and re-install the package.

`rm package-lock.json node_modules` //rm -rf for Linux

`npm install`
