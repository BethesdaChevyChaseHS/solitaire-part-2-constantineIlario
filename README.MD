[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/tzx6F0gN)
[![Open in Codespaces](https://classroom.github.com/assets/launch-codespace-2972f46106e565e64193e422d61a12cf1da4916b45550586e14ef0a7c637dd04.svg)](https://classroom.github.com/open-in-codespaces?assignment_repo_id=17179769)
Setup Steps:
N/A


GameState Description
deck:
-Holds all the cards for the game.
-Starts with a full deck (52 cards) and decreases as cards are drawn or dealt.
gamePiles:
-Represents the seven piles on the board.
visibleCards:
-Stores up to three cards that are drawn from the deck.
discardedCards:
-Holds cards that have been discarded from the visibleCards.


Programming Instructions:
(All code should be added within GameState.java)

1. initializeDeck: Create a full deck of cards by combining all suits and ranks. Use nested for loops to iterate over the enums Suit and Rank. Create a new Card for each combination and push it onto the deck.

2. dealInitialCards: Distribute cards from the deck to the seven gamePiles.
3. drawFromDeck: Draw up to three cards from the deck and add them to visibleCards.
4. discardCards: Should move all cards from visibleCards to discardedCards.

Testing:
Change the test in App.java from 0 to either 1 or 2 to test different parts of your code. 
Test 0 tests initializeDeck and dealInitialCards
Test 1 tests drawFromDeck
Test 2 tests discardCards

NOTE: For all tests, there is no pass/fail, just an ouput of the current state to the console. You need to think about what the game should look like and see if it matches the expectation. 

Submission:
Run the following 3 commands in the terminal:
1) git add . 
2) git commit -m "Submitting my code"
3) git push

Additional Resources:

https://www.geeksforgeeks.org/iterating-over-enum-values-in-java/
https://www.geeksforgeeks.org/stack-class-in-java/
https://www.w3schools.com/java/java_enums.asp
