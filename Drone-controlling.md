# The controller
To control a drone, you need a Drone flyer (or let's just call it a controller). This is what you will use the most when you have a drone.  
The item at the middle is a Drone chip Mk.I
![](http://i.imgur.com/R3W10FR.png)

## Connecting to the drone
At first, drones are not assigned to any frequency. And to be able to control a drone you need to assign a frequency to it.  
You do that by right clicking the controller on an unassigned drone.
![](http://i.imgur.com/1A4TKW4.png)

The controller will also automatically connect to that drone.  
Now think of frequency here like a password to your drone, if someone knows your drone's frequency, they can set their controller to that frequency, and then connect to that drone just by a simple right click. (Note that 1 controller can only control 1 drone at a time, but a drone can be controlled by many controllers simultaneously) 

## Understanding the controller
Now once you have connected/bound/linked/whatever a controller with a drone, right click the controller (make sure you are not looking at the drone). And the controller screen will pop up
![](http://i.imgur.com/0EiDlsQ.png)

Here are what you can do with the screen.
* Change the frequency of the drone and the controller altogether
* Switch controller mode (discuss later)
* Switch drone mode (discuss later)
* Change drone's engine level
* Start drone's path recording
* Unbind/unassign drone frequency

## Disconnect the drone
To disconnect/unbind/release a drone, simply right click the controller on that drone.
![](http://i.imgur.com/wv08UAr.png)

## Re-assign & un-assign drone frequency
When you want to change the drone's frequency, you go to the controller's screen and change the frequency.  
But sometimes you'd want to release the drone from the assigned frequency, maybe because you want to give it to your friend, or you just want to throw it away. Now you'd press "Unbind drone" in your controller screen.  
Remember, anyone who knows your drone's frequency will be able to do those tasks above. That means a hacker can disconnect you from your drone anytime if he knows the password. So make a safe password!

---
# Flying the drone
To fly a drone you need to hold a controller that is connected to the drone.  
Now first open the controller screen, and switch the controller mode to something other than "off". You will see the modes are:
* Targeting: the drone will fly to your crosshair. If you are looking at a door, the drone flies to that door; if you are looking at a pig, the drone flies to that pig.
* Directing: (this mode is not easy to use at all) the drone's flying direction is your looking direction. If you are looking west, the drone flies west, if you are looking down, the drone flies down. If you are spinning, the drone flies in a circle.
* Buttons: you control the drone with WASD, Jump, and Sneak. Make sure the drone is in your view, or else the movement will be hard to predict. W and S moves the drone up and down your screen, A and D moves the drone sideway of your screen. Jumping moves the drone away from you, and Sneaking moves the drone towards you. If you are in camera mode or if the drone is picking you up, then the drone flies like if you are flying.  
  
But that's not enough, those are the modes to control the drone manually, hence you need to switch the drone to "Manual control" mode. If you have the proper mods installed, switch through the drone modes and you will see these modes:
* Hovering: the drone hovers about 1 block above a surface. The drone never moves.
* Manual control: the drone is controlled by the controller (mods that move the drone like mining or return on low battery can not move the drone, since you are controlling it).
* Preset path: the drone flies in a preset path. Mods can move the drone willingly.
* Follow controller: the drone follows you. Mods can move the drone willingly.

---
# Setting drone path
It's cool to control your drone, but you can also assign a path to that drone, then it will continuously fly along that path until receiving further command.  
To set the path to a drone, first you need to set drone mode to either Manual control, or Preset path. Then press "Record path" button.  
Now you will be manually controlling your drone. This is when the drone is remembering the movements.  
Once you are done "writing" the path, either left click or right click the controller, and the drone will remember that path forever.
### Left click adds a loop path to the drone.
A loop path means if the path is A -> B -> C -> D, the drone will fly A -> B -> C -> D -> A -> B -> ...

### Right click adds a back-and-forth path to the drone.
A loop path means if the path is A -> B -> C -> D, the drone will fly A -> B -> C -> D -> C -> B -> A -> B -> ...