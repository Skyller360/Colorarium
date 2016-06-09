### Rules

Every steps you make on the grid transforms the cells colors to your own. 
Color the maximum amounts of cells and then take the gems to transform you cells into points !

### Installation

Colorarium requires [Node.js](https://nodejs.org/) to run.

You need [Express](http://expressjs.com/) and [Socket.IO](http://socket.io/) installed.

```sh
$ npm install express
$ npm install socket.io
```

### Launching

First of all, make an ipconfig in your console to know your own IP address

```sh
$ ipconfig
```

Go into Assets/Scripts/Javascript/Scenes/Title.js and change the url variable to your own ip + the port 8000

```javascript
 // Assets/Scripts/Javascript/Scenes/Title.js line 50
 var url = 'yourOwnIpAddress:8000';
```

After this, open a console, go to the main folder and launch the server.js file using NodeJS.

```sh
$ cd /DirectoryToColorarium
$ node server.js
```

Open a browser and connect to your own Ip adress on the port 8000. (192.168.0.15:8000 for example).

You'll arrive on the main screen and you'll be the host of the game.

Just add other player by connecting to the same url.

When everybody is connected, just click to launch the game !

You'll use the arrow keys to move your character.

### TODOS

Add sprites.
