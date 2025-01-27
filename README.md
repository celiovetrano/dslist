dslist
﻿
GET
Games
http://localhost:8080/games

GET
Game by id
http://localhost:8080/games/1

GET
Game lists
http://localhost:8080/lists

GET
Game by lists
http://localhost:8080/lists/2/games

POST
List replacement
http://localhost:8080/lists/2/replacement

Body
raw (json)
json
{
    "sourceIndex": 3,
    "destinationIndex": 1
}
