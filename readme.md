#Domemaster Photoshop Actions Pack
Version 0.1 - Nov 24, 2012
by Andrew Hazelden


About the Software
-----------------
This is a collection of custom Adobe Photoshop actions that were designed to speed up the fulldome content creation workflow. 

The actions provide tools for converting images from angular fisheye formats to equirectangular panoramas and back, and general utilities for fulldome production.


#Action List

##Transforms:
	 > Inverse Angular Fisheye
	 > Angular Fisheye to Equirectangular Pano
	 > Equirectangular Pano to Angular Fisheye
	 > Rotate 180 Degrees
	 > Rotate 90 Degrees
	 > Horizontal Offset 1024 pixels
	 > Vertical Offset 1024 pixels
	 > Horizontal and Vertical Offset 1024 pixels
	 
##Masking and Selection:
	 > Crop to Selection
	 > Select All
	 > Save Selection
	 > Load Selection
	 > Color Range Selection
	 > Inside Circular 50% Mask
	 > Outside Circular 50% Mask
	 > Fisheye Alpha Channel
	 > Fisheye Layer Mask
	 > Layer Mask from Selection
	 > Layer Mask from Inverse Selection
	 > Enable Layer Mask
	 > Disable Layer Mask
	 > Delete Layer mask
	 
##General Utilities:
	 > 4x4 Guide Grid
	 > Clear Guides
	 > Invert Colors
	 > Background to Layer
	 > Merge Visible
	 > Flatten Image

#Tool Descriptions

##Transforms

###Inverse Angular Fisheye
This action will allow you to inverse an angular fisheye image. This is the effect "rolling" the inside of the fisheye image to the outside of the frame. This effect works best with a 360° degree fisheye image.

The action can be used to quickly turn a regular angular fisheye image into a "tiny planet" style image.

The inverted fisheye effect is acheived by taking your angular fisheye image and doing a polar to rectangular conversion. Then the action rotates the image 180 degrees. The final step is to convert the image from rectangular coordinates back into polar coordinates.

###Angular Fisheye to Equirectangular Panorama
This action converts a full frame fisheye image into a 360° x 180° spherical panorama. This is done with the help of the Photoshop polar to rectangular coordinates filter.

This action can also be used on individual alpha channels by selecting the alpha channel in the Channels tab and then clicking the button for the action.

###Equirectangular Panorama to Angular Fisheye
This action converts a 360° x 180° spherical panorama into a full frame fisheye image. This is done with the help of the Photoshop rectangular to polar coordinates filter.

This action can also be used on individual alpha channels by selecting the alpha channel in the Channels tab and then clicking the button for the action.

###Rotate 180 Degrees
This action will rotate the Photoshop document by 180 degrees. This is useful for changing the up orientation of the angular fisheye and equirectangular images prior to the conversion.

###Rotate 90 Degrees
This action will rotate the Photoshop document by 90 degrees. This is useful for changing the orientation of the angular fisheye and equirectangular images prior to the conversion.

###Horizontal Offset 1024 Pixels
This action slides the image 1024 pixels to the right and wraps the right side of the image around to the left side.

This is useful for changing the content in the center of an equirectangular image. This is also useful for fixing image seams and preparing tiling textures

###Vertical Offset 1024 Pixels
This action slides the image upwards by 1024 pixels and wraps the top side of the image around to the bottom side. This is useful for fixing image seams and preparing tiling textures.

###Horizontal and Vertical Offset 1024 Pixels
This action slides the image upwards and to the right by 1024 pixels and wraps the top and right side of the image around to the bottom side. This is useful for fixing image seams and preparing tiling textures. 

If you are running this action on a 2K square resolution image it will shift the seams on an image's border to the center of the document. After you have finished your cloning or touch-up work you can run the action a 2nd time so the image border will be reset to its original position. 

On a 4K square or 8K square resolution image you will need to run the action multiple time until the seam is shifted into the center of the document.


##Masking and Selection

###Crop to Selection
This action will crop the Photoshop document smaller based upon the currently selected area. The crop command will reduce the image size based upon a square cropping rectangle drawn around the current selection shape.

###Select All
This action will select all of the pixels on the current image layer.

###Fisheye Alpha Channel
This action creates a full frame circular alpha channel.

A common use is to create a single circular alpha channel and then use the "load selection" action to repetitively make circular domemaster shaped boundary selections.

###Fisheye Layer Mask
This action creates a full frame circular layer mask on the currently select layer.

To use this action you must convert all flattened background layers into floating layers. You can do this using the "Background to Layer" action.

###Layer Mask From Selection
This action applies a new raster layer mask based upon the current selection. To use this action you must remove any existing "raster" layer masks from the current layer.

Layer masks are a quick and easy way to temporarily hide content on an image layer. 

After you create a new layer mask you can edit the layer mask by opening the layers tab and clicking on the mask icon to the right of the layer icon. When the layer mask is selected you can paint the mask using the brush tool.

####Layer Mask Editing Tips
When editing a layer mask you can paint regions of the layer visible or invisible by changing the brush color to either white or black.

You can create transparent areas on the layer by using a shade of gray as the brush color when painting the layer mask.
 
If you adjust the brush hardness to 100% you can paint a crisp hard-edged matte. For a nice soft matte edge set the brush hardness to a value between 0 to 80%.

You can view the contents of a single layer mask full-screen by holding down the option key on Mac OS X or alt key on Windows, and clicking on a layer mask thumbnail image in the Layers Tab. 

To exit the full-screen layer mask view you need to click back on the layer's color thumbnail image in the Layers Tab.

You can invert a layer mask by selecting the layer mask thumbnail icon and clicking the invert action button. This will reverse the visible and hidden areas in the layer mask.

###Layer Mask From Inverse Selection
This action creates a new layer mask based upon inverting the current selection. To use this action you must remove any existing "raster" layer masks from the current layer.

###Inside Circular 50% Mask
This action creates a circular layer mask that hides the area inside a circular region in the center of the current layer.

###Outside Circular 50% Mask
This action creates a circular layer mask that hides the area outside a circular region in the center of the current layer.

###Enable Layer Mask
This action will enable the layer mask on the current layer. This is useful for comparing the effects of transparency on the current layer.

###Disable Layer Mask
This action temporarily disables the layer mask on the current layer. This is useful for comparing the effects of transparency on the current layer.

###Delete Layer Mask
This action deletes the layer mask on the current layer.


##General Utilities

###4 x 4 Grid Guide
This action creates a 4 x 4 grid pattern of alignment guides. This grid is extremely useful for making accurate selections in the image when the "Snap to Guides" command is turned on. You can use the grid to make sure the nadir point in the fulldome image is perfect centered.

###Clear Guides
This action will remove all of the guides from the current Photoshop document.

###Invert Colors
This action will invert the image colors of the currently selected layer. This action can be used on color images, layer masks, and alpha channels.

My favorite use of this filter is to invert a grayscale layer mask. This will reverse the visible and hidden parts of the layer mask.

This action can also be used on individual alpha channels by selecting the alpha channel in the Channels tab and then clicking the button for the action.

This action can be used on a layer mask by selecting the layer mask icon in the layers tab and then clicking the button for the action.

###Background to Layer
This action will convert a flattened image from the background layer mode into a floating layer that supports features like layer masks.

The most common use for this action is to prepare an imported picture like a flat Targa .tga file for custom layer masks.

###Merge Visible
This action will merge all of the visible layers into a single layer. 

This action is different than the flatten image command in that it will ignore any hidden layers. You can use the merge visible command to selectively flatten layers by hiding the other layers, elements, and groups you want to keep.

This version of Merge Visible can merge a single layer and bake the layer mask and layer style effects into the final image.

###Flatten Image
This action will merge all of the layers in the current Photoshop document. This is useful for removing transparency from an image, merging layer style effects, vector shapes, and editable text layers into a single raster image.

Please note that any transparent background areas in the image will be filled with a solid color.




* * *

Actions Created by Andrew Hazelden. (c) copyright 2012.

Email: andrew@andrewhazelden.com

Blog: http://www.andrewhazelden.com
