# liri-node-app (LIRI BOT)
Language Interpretation and Recognition Interface to Spotify, BandsInTown, and OMDB
​
## What LIRI BOT does
LIRI will search Spotify for songs, Bands in Town for concerts, and OMDB for movies.

## Overview
The LIRI BOT app captures user input for searching through Spotify, Bands in Town (api is not working), and OMDB databases for matching songs, concerts, and movies. Its Javascript code is contained in a single .js file. There is a random.txt file that contains spotify search instructions, and a logfile *(log.txt)* that records the response data. 
​
## How to run the app
Follow these instructions for running the app:
1. Fork the repository from this link: https://github.com/PetrosyanArt/liri-node-app.
1. Open Terminal and navigate to your __liri-node-app__ repository folder.
1. Use the following syntax after the Terminal prompt:
​
    `$ node liri [database] [search]`
​
In place of [database] enter one of the following options:
* spotify-this-song
* movie-this
* concert-this
* do-what-it-says
​
In place of [search] enter your search word(s).
​
## Sample Terminal output
Here are screenshots of response data as it appears in the console.
​
### Spotify
​
`node liri spotify-this-song mama mia`
​
https://github.com/PetrosyanArt/liri-node-app/blob/master/imgs/spotify-this-song.png
​
### Random text file instructions
​
`node liri do-what-it-says`
​
This input processes instructions in the random.txt file, which is to search Spotify for the song, "I Want It That Way."
​
https://github.com/PetrosyanArt/liri-node-app/blob/master/imgs/do-what-it-says.png
​
### OMDB
​
`node liri movie-this hurt locker`
​
https://github.com/PetrosyanArt/liri-node-app/blob/master/imgs/movie-this.png
​
​
### BandsInTown ______API is not working__________
​
`node liri concert-this beach boys`
​
https://github.com/PetrosyanArt/liri-node-app/blob/master/imgs/concert-this.png
​
## Technologies
Here are this app's NPM modules, databases, switch statement:
​
#### NPM Modules
* node-spotify-api
* axios
* moment
* dotenv
* fs
​
#### Databases
* Spotify
* OMDB
* BandsInTown
​
### Author
Artur Petrosyan