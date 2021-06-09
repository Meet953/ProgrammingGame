# ProgrammingGame

Download the project as zip . 
Unzip and then run ProgrammingApplicationTests class.
If 8080 port is free. rest service API will be hosted on localhost:8080.

Hit url http://localhost:8080/swagger-ui.html#/ to know about the rest end point.

---------------------------------------------------------------------------------------------------------------------------------
Rest end points :

POST /play/api/v1/start?name={}  -  Starts the game by initializing the Player. Creates new player in the game having name passed as param

POST /play/api/v1/move?name={}&column={}  - Adds the move to the board. Player with param name adds a move to the param column.

POST /play/api/v1/disconnect?name={}  -  Disconnects the game for the player with param name

GET /play/api/v1/reset   -   Resets the whole Game. Resets board, players and status. 

GET /play/api/v1/get/state  -   Gets the current playing Game State. Returns status, board and players available at current stage.

---------------------------------------------------------------------------------------------------------------------------------

Alternatively run GameMenuApplication class and play Game from console.
