# **Hangman Wars**
#### Erica Wright, Zach Swanson, Charles Peden & Brendan Grubb, 3/6/2017

&nbsp;
## Description
  Hangman Wars is an interactive word game based on the classic Hangman Game.  Players take on the role of a warlord seeking to conquer the land, and the only path to victory is to empower their soldiers by deducing the secret phrases of the authors of the land.  Each round of play, the player will select an author from the region and be given a hidden phrase taken from their work.  They must guess each word in the phrase letter by letter, and when they guess incorrectly, a soldier dies.  When they guess the whole phrase, their soldiers assault the keep of the castle, and if enough survive, the player may conquer the next region.  When all five regions are conquered, they are declared the victor!


&nbsp;
## Specifications

 user story:

 Player is presented with the map with all areas disabled except col 1, where 2 options.  Player picks an option and difficulty and is transported to the game screen.  Game screen randomly picks a quote associated w/ author and game is played.  At end of phase player has either completely lost and has to start over if failed to guess the phrase, temporarily lost and has to fight another battle in the current map level, or progresses back to the map screen with the next map level opened.  Program determines what realm the win occurred in and opens the next if applicable.  Game state repeats until a win in zone 5, at which point final win.


&nbsp;
## Setup/Installation Requirements
##### _To view and use this application:_
* It is necessary to download and install a few programs to use this application
    * Go to [getcomposer.org] (https://getcomposer.org/) to download Composer (a dependency manager) for free.
    * If you plan on using this app on a mac, go to [mamp.info] (https://www.mamp.info/en/downloads/) to download MAMP for free. If you're not using a mac, make sure you have software installed that allows you to host a web server via Apache and manage a database via MySQL (WAMP, LAMP, etc)
* Go to my [Github repository] (https://github.com/Brendangrubb/hangman-wars)
* Download the zip file via the green button
* Unzip the file and open the **_hangman-wars-master_** folder
* Inside of the **_hangman-wars-master_** folder, unzip the **_hangman_wars.sql.zip_** file
* Open MAMP (or equivalent) and click on preferences/ports.
    * Make sure that the Apache port number is set to 8888 and the MySQL port number is set to 8889
    * Click start servers.
* Type **_localhost:8888/phpmyadmin_** into your web browser
    * Click the _Import_ tab on the nav bar
    * Click _Choose File_ and navigate to the unzipped **_localhost.sql_**
    * click _GO_
* Open Terminal, navigate to **_hangman-wars-master_** project folder, type **_composer install_** and hit enter
* Type **_localhost:8888_** into your web browser
* The application will load and be ready to use!

&nbsp;
## Known Bugs
* No known bugs

&nbsp;
## Technologies Used
* PHP
* Silex
* Twig
* PHPUnit
* SQL
* Apache
* Composer
* Bootstrap
* CSS
* HTML

&nbsp;
_If you have any questions or comments about this program, you can contact me at [brendangrubb@gmail.com](mailto:brendangrubb@gmail.com)._

Copyright (c) 2017 Erica Wright, Zach Swanson, Charles Peden & Brendan Grubb

This software is licensed under the GPL license
