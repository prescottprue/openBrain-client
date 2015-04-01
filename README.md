# Open Brain Client

## Overview
Open Brain Client is a web interface that streams data from [OpenBCI Hub](https://github.com/dgoodwin208/OpenBCI_Hub) through a socketed data connection.

## Development

The Open Brain Client requires running [Open BCI Hub](https://github.com/dgoodwin208/OpenBCI_Hub) (an external UDP server for BCI data) to provide a socketed data stream.

## Installation

1. View/Complete installation section of [OpenBCI Hub](https://github.com/dgoodwin208/OpenBCI_Hub).
2. Run `npm install` and `bower install` within the Open Brain Client directory to install development/content dependencies.

### Getting Started

1. Start the BCI Hub by running `python app.py --simulator` in the OpenBCI_Hub directory.
2. Begin streaming data by visiting `localhost:5000` and clicking the Stream button. Side Note: If you refresh the page you will see the updated page.
3. Run the Open Brain Client by running `gulp serve` within the Open Brain Client directory.
4. Visit `localhost:3000` to start using the Open Brain Client.

## Dependencies

* [AngularJS](http://angularjs.org)
* [D3.js](http://d3js.org/)
* [Socket.io](http://socket.io)
* [OSC.js](https://github.com/colinbdclark/osc.js)
