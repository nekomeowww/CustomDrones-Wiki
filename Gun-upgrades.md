## To upgrade
To upgrade your guns, first you need to craft gun upgrades. Head straight to the crafter, go to "Upgrades" category and craft your upgrades!  
Note: all upgrades require a Chip MkI to craft.

## Upgrades
* Explosion
    * Causes explosion on contact.
    * +10 battery cost
* Scatter
    * Creates more plasma shots with half the velocity and damage of original shot on contact. 
    * Homing shots create 4 sub-shots, non-homing shots create 6 sub-shots.
    * Sub-shots have all the properties/upgrades of the original shot, except the ability to further scatter.
    * +1 & x4 battery cost
* Healing
    * Heal target instead of damaging.
    * +2 battery cost
* Double shot
    * Double the amount of shots each trigger.
    * x1.5 battery cost
* Triple shot
    * Triple the amount of shots each trigger
    * (Double shot and Triple shot can stack to make 6-shot-per-trigger guns)
    * x2 battery cost
* Fire
    * Causes fire, thaw snow & ice.
    * +5 battery cost
* Ice
    * Extinguish fire, freeze water, cast snow.
    * +5 battery cost

Example of a Homing plasma gun with Scatter and Explosion upgrades
![](http://i.imgur.com/haTQlDU.gif)

## Understanding battery cost
You've seen something like +5 battery cost and/or x2 battery cost. The first is called "additional cost", and the latter is called "cost scale". If not stated then "additional cost" is 0 and "cost scale" is 1.  
They work like this:
* First add all "additional costs" from upgrades to the original 10+ battery/shot cost.
* Then multiply the added cost with all the "cost scales" from upgrades to get the total cost.
  
For example, you have a Homing plasma gun with Scatter and Explosion installed, shooting at a sheep 16 blocks away.
* First, the battery cost is 10.
* Second, the "homing" battery cost is 4 (square root of 16)
* Third, the "additional cost" is: 1(scatter) + 10(explosion) = 11
* Fourth, the "cost scale" is: 4(scatter) x 1(explosion) = 4
* Finally, the total cost is (10 + 4 + 11) x 4 = 100 battery/shot