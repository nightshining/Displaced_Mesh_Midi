## Description:

A software based midi controller that utilizes a 3d deformation of a mesh to control notes + cc parameters on a hardware or virtual device that supports midi input

![](https://github.com/nightshining/Displaced_Mesh_Midi/blob/master/assets/app.gif)

## How to use:

* [Download Touch Designer](https://derivative.ca/download)

* Open up the *Displace_Mesh_Midi.toe* file

* Make sure you *MIDI Device Mapper* within the Dialogs dropdown is set to the proper in/out MIDI device

![](https://github.com/nightshining/Displaced_Mesh_Midi/blob/master/assets/midisetup.png)

* Click on the *open viewer* button to open the render window (this is where the UI elements exist)

![](https://i0.wp.com/farm4.staticflickr.com/3728/10622193793_2d8fbed535_o.jpg)

* Choose which notes or control values you would like to alter by adding in a channel / note OR cc / parameter value seperated by a comma ',' with no spaces 
 * ch1n = MIDI note index
 * ch1c = MIDI control parameter index
![](https://github.com/nightshining/Displaced_Mesh_Midi/blob/master/assets/ui.png)


* Now you can start using the dial knobs to change parameters on the 3d mesh to start alterning your MIDI cc + note outputs. CC's correspond to the positional data of each vertex, Note data gets triggered by a threshold of when vertex data passes specific 3d spatial areas. 

