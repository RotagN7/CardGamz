# CardGamz
Card Games application. 

Initial Thoughts:

Enum Status {
Hit,
Stay,
Fold,
Call, etc; 
}

class Card {
String suite;
String value;
}

class Player {
  String name;
  List<Card> hand;
  Status status;
}
  
 ...maybe an AbstractPlayer class to creat a different type of player for each game.... maybe...
  
class Deck {
  Card[] deck
  
  //instantiate deck blah-blah
}

class Blackjack(int numberOfPlayers, ...maybe some options added in the future like value of aces, jokers in session, etc.) {
  
  startGame() {
    while(goAroundTable) {
      //print status
      goAroundTable()
  }
  
  boolean goARoundTable() {
    //loops through players asking if they want to hit or fold
    //checks the status at end and returns false if and only if the status of each player is Stay and/or Busted
  }
}

class Game
