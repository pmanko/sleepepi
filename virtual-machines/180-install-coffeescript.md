## 180 Install Node.js and CoffeeScript JavaScript compiler

Tools required by server to compile CoffeeScript files into JavaScript

The following requires that [gcc 4.9.4 or higher is installed](https://github.com/sleepepi/sleepepi/blob/master/virtual-machines/910-gcc.md), install Node.js v6.13.1 if gcc cannot be updated.

### 181 Node.js and Node Package Manager

Download and compile node.js and Node Package Manager

```
cd ~/code/source
curl -L https://nodejs.org/dist/v10.15.3/node-v10.15.3.tar.gz | tar xvz
cd node-v10.15.3/
./configure
make
sudo make install
```

Verify Node.js installed by typing `which node` which should return:

```console
/usr/local/bin/node
```

Verify Node.js version by typing `node -v` which should return:

```console
v10.15.3
```

Update npm:

```console
sudo npm install -g npm
```

Verify npm installed by typing `which npm` which should return:

```console
/usr/local/bin/npm
```

Verify npm version by typing `npm -v` which should return:

```console
6.9.0
```

Make symbolic links for node and npm

```
sudo ln -s /usr/local/bin/node /usr/bin/node
sudo ln -s /usr/local/bin/npm /usr/bin/npm
```

### 182 CoffeeScript

Download and compile CoffeeScript

```
sudo npm install -g coffeescript
```

Verify CoffeeScript installed by typing `which coffee` which should return:

```console
/usr/local/bin/coffee
```

Make symbolic links for coffee

```
sudo ln -s /usr/local/bin/coffee /usr/bin/coffee
```

Verify CoffeeScript version by typing `coffee -v` which should return:

```console
CoffeeScript version 2.3.2
```

### Next Step

[190 - Install Rails Applications](https://github.com/sleepepi/sleepepi/tree/master/virtual-machines/190-install-rails-applications.md)
