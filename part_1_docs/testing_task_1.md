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

  # There is a = missing, it should be "if card.value == 1:" 
  # there is also a ":" missing affter the "else"

  def check_for_ace(self, card):
    if card.value = 1:
      return True
    else
      return False
   
  # there is a "," missing from between "card1 card2" in the parameters part of the function. 
  #it also needs to be called "def" not "dif
  # the rest of the code after the first line needs to be indented. 
  #it returns "card", needs to be "card1" in the first conditional return

  dif highest_card(self, card1 card2):
  if card1.value > card2.value:
    return card
  else:
    return card2
  
# total needs to be set to 0 like "total = 0" before the loop
# the return needs to not be in the loop because it will end the loop after the first card
# the whole function needs to indented one more time
# the return value needs to be changed to a str

def cards_total(self, cards):
  total
  for card in cards:
    total += card.value
    return "You have a total of" + total
  
```
