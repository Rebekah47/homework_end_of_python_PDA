### Testing task 1:

# Carry out static testing on the code below.
# Comment on any errors that you see below.

Note that we are only looking for errors here.

**Not** any issues with, i.e.: 
Thinking that methods should be renamed or should be class level, or using string interpolation etc. 

These aren't errors but rather standards that vary from developer to developer. 

Only comment on errors that would stop the tests running.

```python

class CardGame:


  def check_for_ace(self, card):
    if card.value = 1: #needs two equals signs
      return True
    else #needs a colon here or the test will call and funtion with a sytax error that wont return the right boolean 
      return False
   

  dif highest_card(self, card1 card2):#function isnt defined so the test won't be able to find it and needs a comma between card1 and card2.
  if card1.value > card2.value:
    return card #needs the specify card1, there is no variabel card
  else:
    return card2
  


def cards_total(self, cards):
  total#variable isnt defined and so the function wouldnt return anythign to test ,needs to be and int, set to 0
  for card in cards:
    total += card.value 
    return "You have a total of" + total #return statment is indented too far and is inside the for loop and the "total" needs to be concatenated in to a string.
  
```
