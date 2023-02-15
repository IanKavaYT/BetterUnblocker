Evade internet censorship!

The original nodeunblocker.com is gone, but it's now easier than ever to deploy your own copy.

[![Deploy to Cyclic](https://deploy.cyclic.sh/button.svg)](https://deploy.cyclic.sh/)
## Now with YouTube support (sort of)


## Running the website on your computer

1. Install [node.js](http://nodejs.org/)
2. [Download the code](https://github.com/nfriedly/nodeunblocker.com/archive/master.zip)
3. Unzip it
4. Open up a terminal/command line
5. `cd` into the directory
6. Run `npm install` to grab the dependencies.
7. Run `npm start` to start the server. It should spawn a new instance for each CPU core you have.

(Note: running `node app.js` *will not work*. The server code is in the [Gatling](https://npmjs.org/package/gatling)
package, which the `npm start` command calls automatically.)

After that, it will be live on your computer and accessible from your computer at http://localhost:8080/ - accessing it from another computer is beyond the scope of this guide, but it is possible.


