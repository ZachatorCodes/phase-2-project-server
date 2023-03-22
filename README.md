# Bunk Sales Database Backend Server

Bunk Sales is a web search application that can be used to find the best price for any given PC game, given that there are active deals happening.

Additionally, the application can also be used to find all deals for a given online marketplace, as well as to save a user's favorites games to a "favorites" database.

## Installation

- To begin, please make sure that you've already forked and clone the frontend repository for [Bunk Sales](https://github.com/ZachatorCodes/phase-2-project).

- In order to install the backend server for Bunk Sales, first ```fork``` and ```clone``` this repository to your local device.

- Make sure you are in the directory with the db.json file (/db), then run ```json-server --watch db.json --port 4000``` This will run the json server on port 4000, which is the port that Bunk Sales fetches information from.

- IMPORTANT: if you do not have json-server installed, you will need to install it to host the backend server. Please follow the installation instructions found on [JSON Server's NPM Page](https://www.npmjs.com/package/json-server). To install the package globally, add the ```-g``` tag in between install and json-server.

Normal Install: ```npm i json-server``` or ```npm install json-server```
Global Install: ```npm i -g json-server``` or ```npm install -g json-server```