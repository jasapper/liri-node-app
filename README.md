# liri-node-app (aka LIRI Bot)

LIRI Bot is a command line Node app that takes in parameters you provide and gives you back data. LIRI is like iPhone's SIRI. However, while SIRI is a Speech Interpretation and Recognition Interface, LIRI is a _Language_ Interpretation and Recognition Interface.

Currently this LIRI Bot supports the following (fairly ubiquitous) services:
- Twitter
- Spotify
- Open Movie DataBase (OMDB)

### Installation
_NOTE: Node.js (and it's associated node package manager) are required to use this app._ Installation of Node.js is outside the scope of this README.
After cloning or downloading the repository enter the new directory created and enter:

`npm install`

You are now ready to begin!

### Usage
`node liri.js [tweet-this | spotify-this-song | movie-this | do-what-it-says]`

For Spotify and OMDB an additional search parameter can be specified.

OMDB example:

`node liri.js movie-this spaceballs`


### See the app in action!

![Alt Text](https://github.com/jasapper/liri-node-app/raw/master/lira-node-app.gif)