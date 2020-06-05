# Project design

- Create cosmos address and it is your planet
- There's denom for size, gold and food, attack power and efficiency and defence power and efficiency but it shouldn't be transferable.
- You can purchase land and it is increasing the weight value of your planet which increase the limit of gold, food and items count.
- You can split out the attack power, food and efficiency and defence power and efficiency from the planet into an item to attack other planet.
- You can update soliders by training them.
- There are small bot planets that you can attack and it randomly appear within cosmos

Here's rule for fighting between planets

Defence power (planet)
- sum (power * defence efficiency)

Attack power (attack item)
- sum (power * attack efficiency)

Result
- As time goes, power of both side decrease (Is this possible to do like this?)
defence power -= attack * attack efficiency
attack power -= defence * defence efficiency

- If one defeat another by defence, defence efficiency increase and attacker die.
- If one win another by attack, attack efficiency increase, and get all gold and food from that planet and defencer die.


