### Testing task 1:

# Carry out static testing on the code below.
# Comment on any errors that you see below.
```ruby

class CardGame


  def checkforAce(card)
    if card.value = 1 # It should be "==" "comparatively equal to" in the method body.
      return true
    else
      return false
    end
  end

  dif highest_card(card1 card2) # sould be "def not "dif" and a comma between the parameters.
  if card1.value > card2.value
    return card # card1
  else
    return card2
  end
end
end # this will end the class "CardGame"

def self.cards_total(cards) # "self" wont be executed because its in the method prototype.
  total # total has not been assigned a vlaue 
  for card in cards
    total += card.value
    return "You have a total of" + total # this should be after the first end as it will return after this first iteration.
    # total needs to be interpolated or converted into a string
  end
end
# missing a closing end
