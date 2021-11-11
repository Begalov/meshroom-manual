Image Viewer
============

Controls
++++++++

Drag:

* left mouse + shift
* middle mouse

Zoom: scroll wheel

Context menu: right mouse

Display Features
++++++++++++++++

Display an overlay showing the features used in the reconstruction.

The three switch buttons with corresponding numbers are, in order from left to right, the number of extracted features, the number of matched features, and the number of features that have been reconstructed.

Select Image Type
+++++++++++++++++

Input image, depth map and sim map can be viewed.
Double click either a ``DepthMap`` or ``DepthMapFilter`` node to view the outputs of that node.

View Depth Map In 3D
++++++++++++++++++++

The depth map will be loaded into the 3D viewer.
Be aware that lots of RAM is used.

``StructureFromMotion`` Statistics
++++++++++++++++++++++++++++++++++

There are 2 types of statistics that can be shown:

Statistics for that paticular image is the reprojection errors, observations scale, observations lengths.

Global statistics are residuals per view, landmarks per view, observations lengths per view.

Image Metadata
++++++++++++++

All of the metadata associated with that image such as make and model.
