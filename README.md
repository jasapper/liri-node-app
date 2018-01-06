# liri-node-app (aka LIRI Bot)

LIRI is like iPhone's SIRI. However, while SIRI is a Speech Interpretation and Recognition Interface, LIRI is a _Language_ Interpretation and Recognition Interface. LIRI is a command line node app that takes in parameters you provide and gives you back data.

Currently this LIRI Bot supports the following (fairly ubiquitous) services:
- Twitter
- Spotify
- Open Movie DataBase (OMDB)

### Installation
_NOTE:_ Node.js (and it's associated node package manager) are required to use this app. Installation of Node.js is outside the scope of this README.
After cloning or downloading the repository enter the new directory created and enter:
`npm install`
You are now ready to begin!

### Usage
`node liri.js [my-tweets|spotify-this-song|movie-this|do-what-it-says]`
For Spotify and OMDB an additional search parameter can be specified.
For example:
`node liri.js movie-this spaceballs`