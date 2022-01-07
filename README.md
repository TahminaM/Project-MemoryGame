# Project:   MemoryGame

Introduction:
Two-face cards with content-side facing down.
In each round, flip two cards. 
  Flip the card by entering an integer representing an index, starting from 0. In our example, the last index is 7, so the input should be in [0, 7].     Suppose we select 3.
  After the first flip, the content of the card, which can be an integer, is shown.
  
Second flip in a round match to first flip:
  Afterwards, flip the second card.
  If the integer of the second card matches that of the first one, the second card is opened; otherwise, close both cards. 
  Suppose we choose 5, since both space 3 and 5 have the same number, we find a match.
  
Second flip in a round not to match to first flip:
  Suppose we choose 6. Since Card 6 does not have the same number as that of the first flip, ie, Card 3, in this round,  both cards are turned.
  
Continue until all matched numbers are found:
 To make the game challenging, add cards whose sides are both empty.
    In a round, if the first flip shows an empty face (ie, no integer disclosed), then this card has two empty faces. In this case, we cannot tell         whether the second flip has an integer or not.
 Stop until all matched twin integers are found. 
 Report the total number of flips to find out all matches. 
    Print out “Congratulations! Take … steps to find all matched pairs.”, where … is the number of steps.
