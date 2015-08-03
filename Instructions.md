# Summary #

There are several uses for this programme one of its intended uses is to load models and view their animations.

Once selected those animations can then be saved as individual AnimationClip files.  The AnimationClip files can then easily be loaded in to an XNA game project.

- Load an animated model.  It does not matter if it has animations or not but must have the armature ready to animate.

- Load FBX (or X) files that contain an animation for that model.  It can only load the first animation in the file.  (That is the limitation of the Autodesk FBX importer shipped with XNA 4.0)

You can load several animations and select between them using the drop down selection box.  The currently selected animation will play.

## Other Uses ##

The application can also be used to split FBX files that have multiple animations in to separate files.

There are sections unique to my games that create bounds for the model.


# Details #

On the File menu there is an option to _Load Animated Models..._  Loading a model clears all previously loaded animations.  So the model must be loaded first.

Also on the File menu there is a separate option to _Load Animations..._  Load as many of these as you like.  It only loads the first animation from the file.

To create suitable animations it is necessary from your 3D drawing programme to export each animation in to a separate FBX file.  In Blender that is done by selecting the action in pose mode and Exporting to FBX.  See my related project for Blender 2.5 FBX export scripts suitable for XNA.

http://code.google.com/p/blender-to-xna/