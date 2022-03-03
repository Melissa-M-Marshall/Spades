Requirements: 
  Operate a game of spades successfully between four players. For initial simplicity, the program will run a game between a player and several computers, 
  and will provide the option to input how many players will be human.
  All cards should be displayed clearly to the human players; other players should not be able to see the others' cards.
  Each "round" consists of 13 plays, each of which will give one of the playera a trick.
  Highest number wins a play; ace is highest value, then king, queen, jack, and then all numbers follow usual numeric order.
  Spades win a play if they are the only spade in play; if not, highest spade wins.
  Spades can only be played if a) the play is initiated as a "spade" round or b) the player has no cards of the type being played(ie, ran out of hearts, diamonds, clubs). 
  If a player wins a play, they start the next play.
  For the very first round of play, "player 1" will start the round. This then rotates clockwise around the group (ie, for second round, player 2 goes first).
  Each player can select their own bid, based on what cards they have. If the bid is successfully reached, the player gets ten points per expected trick, and one point per unexpected trick.
  If a player misses their bid, they lose as many points as they would have gained.
  If a player hits ten unexpected tricks, they lose 100 points.
  
  FOR FUTURE: try to add nil, and shoot the moon options for the bids. For now, expect that everyone will bid at least one, and less than 13.
  
Domain Class Diagram:
  ![Domain Class Diagram 1](https://user-images.githubusercontent.com/65798296/156659955-9943d8ef-7caf-40ec-b560-e404cf6c3bc8.png)

Use Case Diagram: 
  ![UseCase Diagram 1](https://user-images.githubusercontent.com/65798296/156662302-659d392c-eb3c-4db6-a932-735e727f6a19.png)

  
