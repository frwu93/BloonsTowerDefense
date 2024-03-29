Bloons Tower Defense
====

This project implements a player for multiple types of Bloons Tower Defense modes.

Names: Jack Ellwood, Jason Qiu, Franklin Wu, Annshine Wu, Eddie Dong


### Timeline

Start Date: 10/23/2020

Finish Date: 11/19/2020

Hours Spent: 60-70

### Primary Roles

* Jack: Front-end menus and visualization
* Jason: Bloons and other back-end components
* Franklin: Controller and integration between model and view
* Annshine: Towers, Projectiles, Road Items, Shooting Interactions, and Bank
* Eddie: Front-end in-game buttons, tower placement, and other game objects

### Resources Used

Stack Overflow
Refactoring Guru
Various Resources Provided on Website
Java Docs
Baeldung

### Running the Program

Main class: Main.java

Data files needed: Various properties files, csv files, css files, and images

Features implemented:
 * Implemented different game modes, including normal, infinite rounds, and "sandbox," with infinite money
 * Ability to add new levels through properties and csv files
 * Multiple types of Bloons, Towers, and Projectiles
 * Multiple language and style options

### Notes/Assumptions

Assumptions or Simplifications: Probably our biggest assumption or requirement is the use of a CSV file to determine the path of enemies or bloons on the level layout.  The elements of the CSV must correspond to a certain pattern in order for Bloons to move properly through the level. Bloon wave files (which determine the bloons that appear in a certain round) also have a certain format that corresponds to types of bloons, the order in which they appear, and the separation between bloon waves. Another assumption is that the BloonsType property file will have the bloons types listed in the order of the chain as listed in the order key. Additionally, there should not be conflicting information in regard to what bloons come next. Finally, the bloon types should always include DEAD which is always the first bloon in the chain. 

Interesting data files: level1.csv in bloon_waves offers a good example of how a bloon wave is formatted and read into the game. gameMenu.properties is an example of how we used data-driven design to make the game window size and various front-end features customizable.

Known Bugs: Sometimes a Bloon that is shot at on the edge of the screen will result in a crash. Also, special bloons such as Camo and Regen bloons may
not disappear once killed, which is something we hope to continue to be able to debug.

Extra credit:

### Impressions

Overall, a very challenging assignment that we all learned a lot from.  We feel we produced a well-developed and extendible game architecture and are proud of how far we've come in the process. Additionally, we have learned a lot about design and thinking extensibily and separating our design into different components such as Model, View, and Controller. Additionally, we learned a great deal about what it means to work on a team and the responsibilities it requires for all parties involved.
