# Chess
This is an upgraded version of [almatrass/chess-site](https://github.com/almatrass/chess-site)
This version contains better CSS styling, JS game code checking mechanism.

**This project does not work on mobile**

> *Has been tested on **Google Chrome**, **Edge**, **FireFox**, **Chromium**, and **Opera** web browsers.*

<hr>

### Instructions (of use): 

> Live website: https://chess-website-completed.onrender.com/
> 
> **Note: This might load upto a minute**

Create a game by typing in a random game code and then pressing "Create game".

<img src="https://github.com/marsianjohncarter/Chess/assets/116607327/0efccd5f-902c-4189-a5c6-5e57de7a500c" width="500" height="200">

Join a game by typing in the random game code that you entered earlier and then pressing "Join game".

<img src="https://github.com/marsianjohncarter/Chess/assets/116607327/013506ec-bfeb-4c55-8635-b467e08a94d8" width="500" height="200">


You will then be able to play a chess game with whoever connects with you onto your game.
<img src="https://github.com/marsianjohncarter/Chess/assets/116607327/bd160133-6e9b-4b57-98b3-2b7783ae8bb1" width="500" height="550">
<hr>

## Dependencies:

|      Library      |    Version     |
|-------------------|----------------|
|dotenv             | ^16.3.1        |
|express            | ^4.18.2        |
|express-handlebars | ^7.0.7         |
|http               | ^0.0.1-security|
|path               | ^0.12.7        |
|socket.io          | ^4.7.2         |


### Instrctions (building and deploying on local network):

To install dependencies:

```
npm i
```

To start:

```
node ./server/server.js
```