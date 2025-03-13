# Setting up a new project for 3D printing in Blender
## Create a New Project
* File > New > General
* Save the Project: File > Save (<kbd>Ctrl</kbd> + <kbd>S</kbd>)

## Remove the movie set
As blender was made for animated scenes in mind, it comes with a camera and light in the default setup. We do not need these.

In `Object Mode` (<kbd>Ctrl</kbd> + <kbd>Tab</kbd>, <kbd>4</kbd>)
* Use `Select Box` (<kbd>Space</kbd>,<kbd>b</kbd>)
* Select the camera object (top left in scene or `Camera` in the collection pane)
* Press <kbd>x</kbd>
  * if done in the collection pane: that's it. The object is removed
  * if done in the 3D Viewpoint (<kbd>Shift</kbd> + <kbd>F5</kbd>): Confirm with <kbd>Enter</kbd> or <kbd>Alt</kbd> + <kbd>d</kbd>)

## Measurement Units (size) to mm instead of m for more accuracy
1. Properties (<kbd>Shift</kbd> + <kbd>F7</kbd>) > Scene Properties > Units > Length: Millimeters / Unit Scale: 0.001
1. 3D Viewpoint (<kbd>Shift</kbd> + <kbd>F5</kbd>) > Viewport Overlays Settings ![Viewport Overlay Settings](./media/ViewportOverlaysSettings.png) > Scale 0.001

## Credits / Sources
[YouTube Video 'Learn Blender for 3D Printing - Complete Quick and Easy Guide (Beginner)' by '3D Printer Academy Tutorials'](https://www.youtube.com/watch?v=rN-HMVTB7nk&list=PL_nLm_Ns-0xGd9a_uwIjrhfZx1tcxQmoc)