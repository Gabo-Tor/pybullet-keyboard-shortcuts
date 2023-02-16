# pybullet keyboard shortcuts
PyBullet keyboard shortcut/hotkeys list

I have found no hotkeys list anywhere in the web, hope that at some point i can add it to the official quiskstart guide.

I am a user of Pybullet and this is the list I was able to compile reading the sourcecode, different forum posts and experimenting, all of these have been tested and work in current versions of pybullet unless noted otherwise. 

 ## Hotkeys list

|Action   |Operation	   |Instruction   |
|---|---|---|
| Show collision boxes                        |  a | Press a with wireframe rendering activated to show axis-aligned bounding box (AABB) |
| Visualize the constraint frames             |  c | Press c with wireframe rendering activated to visualize collisions(contact points) |
| Toggle auto-deactivation of the simulation  |  d* | Press d to toggle auto-deactivation of the simulation |
| Open/close the search, test and params tabs |  g | Press g to toggle all tabs and menus|
| Suspend/restart physics simulation          |  i* | Press i to pause simulation |
| Show links and joints frames as RGB lines   |  j | Press j with wireframe rendering activated to show links and joints frames as RGB lines |
| Show joint axes as a black line             |  k | Press k with wireframe rendering activated to show constraints (joint axes) |
| Visualize the constraint limits             |  l | Press l with wireframe rendering activated to show constraint limits  |
| Single step simulation                      |  o* | Press o for single step simulation |
| Profile dumping                             |  p | Press p to for profile dumping, prints or logs thread usage |
| Toggle ligths and shadows                   |  s | Press s to toggle lights and shadows |
| Toggle visual geometry                      |  v | Press v to toggle visualization of geometry faces |
| Toggle wireframe                            |  w | Press w to toggle wireframe mode |
| Exit app                                    |  Esc | Press Esc to exit the simulator |
| Move object                                 |  click + drag | click on an object within the simulation to apply a force |
| Rotate view                                 |  Ctrl + drag | When holding the Alt or Control key, left mouse click and drag rotates the camera |
| Translate view                              |  Ctrl + middle click | When holding the Alt or Control key, middle mouse click and drag moves the camera |
| Zoom view in/out                            |  mouseweel  |  Use the mouseweel to zoom in and out |
| Zoom view in/out                            |  Ctrl + right click | When holding the Alt or Control key, right mouse click and drag zooms camera in and out |
| Toggle image dump Physics Server            |  F1 | Press F1 to toggle image dump Physics Server (saves screenshots of the simulator to the /home directory continuously) |
| Save a 'testFile.bullet'                    |  F3* | Press F3 key in most of the Bullet examples to save a 'testFile.bullet' |


*Migth have no effect on some simulations

## Contributing
Opening issues and pull requests are welcome to fix bugs and to extend this cheat sheet.

## Useful links
- [PyBullet Quickstart Guide](https://docs.google.com/document/d/10sXEhzFRSnvFcl3XxNGhnD4N2SedqwdAvK3dsihxVUA/edit#heading=h.2ye70wns7io3)
- [Web Page](https://pybullet.org/wordpress/)
- [Bullet source code](https://github.com/bulletphysics/bullet3)
- [File where most of the keys are parsed](https://github.com/bulletphysics/bullet3/blob/5ae9a15ecac7bc7e71f1ec1b544a55135d7d7e32/examples/ExampleBrowser/OpenGLExampleBrowser.cpp)
