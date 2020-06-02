# Project design

- Create cosmos address and it is your planet
- There's a planet describer item that has weight, gold and food. The item name is "planet-<cosmos_address>"
- You can purchase land and it is growing the weight value of your planet which increase the limit of gold, food and items count.
- There are combat soliders associated with the planet with power, experience, attack strength, defence strength.
- You can update combat soliders by giving them exercise.
- There are small bot planets that you can attack and it randomly appear within cosmos

Here's rule for fighting between planets

Defence power
- sum (power * defence efficiency)

Attack power
- sum (power * attack efficiency)

Result
- As time goes, power of both side decrease 
defence power -= attack * attack efficiency
attack power -= defence * defence efficiency

- If one defeat another by defence, defence efficiency increase
- If one win another by attack, attack efficiency increase, and get all gold and food from that planet.


