# ZombieGame_AI
Using a custom framework mainly specializing in adding methods and subjects related to AI, this project aims to create an AI that can survive a zombie apocalypse.
To run this project without opening the solution, navigate to the DEBUG_RELEASE folder.
You can run the normal executable to open the simulation in one window OR run the .bat file to run 4 instances of the simulation at once. This allows you to see the AI in action multiple times at once.

In this game, the AI must find supplies stored within houses. It knows what a house is when it is within its cone of vision. 
It must find the mentioned houses and supplies within to satisfy its ENERGY levels (hunger), restore its HEALTH when bitten by zombies, and find guns.
There is also a chance that the AI will simply find trash and therefore decide to remove it from its inventory.

As time goes by the game gets more difficult including adding DANGER ZONES that instantly kill the bot if it is in the radius of the zone once a timer runs out.
The bot is also always pursued by zombies including special TANKS that have more health and are therefore more difficult to kill.

The purpose of this project is to make an efficient AI that handles resource management, search and collection of items, finding and killing zombies, and generally surviving for as long as possible.
The bot also has the ability to sprint at the cost of using more energy during the time spent sprinting.
This project employs various methods of achieving these ends such as behavior trees, blackboards, and logic state machines.
