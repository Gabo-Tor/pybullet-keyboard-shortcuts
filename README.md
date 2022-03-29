# pybullet-keyboard-shortcuts
PyBullet keyboard shortcut/ hotkeys list
I have found no hotkeys list anywhere in the web, hope that at some point i can add it to the official quiskstart guide
Im a user of Pybullet and this is the list I was able to compile through my own reasearch and different forum posts, all of these have been tested and work in current versions of pybullet, I'm yet to find the lines of code in the Bullet sourcecode where this keys are parsed


 ## Hotkeys list

|Action   |Operation	   |Instruction   |
|---|---|---|
| Open/close the search, test and params tabs |  g | press g to toggle all tabs an menus|
| Toggle wireframe                            |  w | press w to toggle wireframe mode|
| Show links and joints frames as RGB lines   |  j | press j with wireframe rendering activated to show links and joints frames as RGB lines |
| Show joint axes as a black line             |  k | press k with wireframe rendering activated to show joint axes as a black line  |
| Visualize the constraint limits             |  l | press l with wireframe rendering activated to visualize the constraint limits  |
| Show collision boxes                        |  a | press a with wireframe rendering activated to show collision boxes  |
| Toggle ligths and shadows                   |  s | press s to toggle lights and shadows  |
| Toggle faces                                |  v | press v to toggle visualization of all the simulation  |
| Profile dumping                             |  p | press p to for profile dumping, prints thread usage(? |
| Toggle image dump Physics Server            |  F1| press F1 to toggle image dump Physics Server (saves screenshots of the simulator to the /home directory continuously) |
| Move object                                 |  click + drag | click on an object within the simulation to apply a force |
| Rotate view                                 |  Ctrl + drag | When holding the Alt or Control key, you have Maya style camera mouse control |
| Translate view                              |  Ctrl + middle click | When holding the Alt or Control key, you have Maya style camera mouse control |
| Zoom view in/out                            |  mouseweel  |  Use the mouseweel to zoom in and out |
| Zoom view in/out                            |  Ctrl + right click | When holding the Alt or Control key, right mouse click and drag zooms camera in and out |
|                                             |    |   |
| Suspend/restart physics simulation          |  i* | press i to toggle physics simulation |
| Visualize the constraint frames             |  c* | press c to visualize the constraint frames |
| Save a 'testFile.bullet'                    |  F3* | key in most of the Bullet examples to save a 'testFile.bullet' |
| Toggle auto-deactivation of the simulation  |  d* | toggle auto-deactivation of the simulation |

*this did not work for me

## Useful links:
- [PyBullet Quickstart Guide](https://docs.google.com/document/d/10sXEhzFRSnvFcl3XxNGhnD4N2SedqwdAvK3dsihxVUA/edit#heading=h.2ye70wns7io3)
- [Web Page](https://pybullet.org/wordpress/)
- [Bullet source code](https://github.com/bulletphysics/bullet3)
