#Domemaster Photoshop Actions Pack
Version 0.1 - Nov 24, 2012
by Andrew Hazelden


About the Software
-----------------
This is a collection of custom Adobe Photoshop actions that were designed to speed up the fulldome content creation workflow. 

The actions provide tools for converting images from angular fisheye formats to equirectangular panoramas and back, and general utilities for fulldome production.


#Action List

_This list is a work in progress_

##Transforms:
	 > Inverse Angular Fisheye
	 > Angular Fisheye to Equirectangular Pano
	 > Equirectangular Pano to Angular Fisheye
	 > Rotate 180 Degrees
	 > Rotate 90 Degrees
	 > Horizontal Offset 1024 pixels
	 > Vertical Offset 1024 pixels

##General Utilities:
	 > 4x4 Guide Grid
	 > Clear Guides
	 > Invert Colors
	 > Background to Layer
	 > Merge Visible
	 > Flatten Image

##Masking and Selection:
	 > Crop to Selection
	 > Select All
	 > Fisheye Alpha Channel
	 > Fisheye Layer Mash
	 > Layer Mask from Selection
	 > Layer Mask from Inverse Selection
	 > Inside Circular 50% Mask
	 > Outside Circular 50% Mask
	 > Disable Layer Mask
	 > Delete Layer mask
	 > Save Selection
	 > Load Selection
	 > Color range Selection

# Action Pack Tool Descriptions

## Inverse Angular Fisheye 


What does this action do?
-------------------------
This is a Photoshop action that will allow you to inverse a 360 degree angular fisheye image. This has the effect of "rolling" the inside of the fisheye image to the outside of the frame.

The action can be used to quickly turn a regular angular fisheye image into a "tiny planet" style image.


How does it work?
-----------------
In the first step the Photoshop action takes your angular fisheye image and does a polar to rectangular conversion.

Then the action rotates the image 180 degrees.

The final step is to convert the image from rectangular coordinates back into polar coordinates.




* * *

Actions Created by Andrew Hazelden. (c) copyright 2012.

Email: andrew@andrewhazelden.com

Blog: http://www.andrewhazelden.com
