# README

This website is an attempt to recreate a MIDI controller using the keyboard. Basically, an online launchpad, similar in function to that of Novation's Launchpad.

Features:

* Uses Howler JS audio library for quick and easy audio playing across multiple browsers: http://goldfirestudios.com/blog/104/howler.js-Modern-Web-Audio-Javascript-Library

* Uses the Zip.js library to parse .zip files: https://gildas-lormeau.github.io/zip.js/

* First of the Year Eqninox by Skrillex sounds, obtained from Nev's project file: https://www.youtube.com/watch?v=SAXpBgkXt60

* Editor Capable of recording and playing back keyboard inputs at varying playback speeds

* Able to load and save songs to a database, only available to those who have registered an account which can only be done from the console

* mySql test database and Postgres production database

* Hosted on Heroku with free hobby plan

* Front-end written in complete JS with Ruby on Rails for the back-end, a few ajax requests to backend for information

TODO:

* Downloadable offline version, probably zipped JS, CSS, HTML, and audio files, will have to get rid of server calls

* Finish editor tools and put recorded parts of songs on main page

# DEPLOYMENT

To use this launchpad you can run this docker container: `docker run --rm -d -p 3000:3000 fpekal/launchpad`.  
And then connect to `http://localhost:3000`.
