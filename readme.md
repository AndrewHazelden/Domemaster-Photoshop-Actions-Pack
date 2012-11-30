#Domemaster Photoshop Actions Pack
Version 0.3 - Nov 28, 2012 - Build 5
by Andrew Hazelden


About the Software
-----------------
The Domemaster Photoshop Actions Pack is a collection of custom Adobe Photoshop actions that were designed to speed up the fulldome content creation workflow. 

The actions provide tools for converting images from several common panoramic formats such as angular fisheye, equirectangular, and cube map panoramas, and general utilities for fulldome production.

![Domemaster Photoshop Actions Pack](https://raw.github.com/AndrewHazelden/Domemaster-Photoshop-Actions-Pack/master/Screenshots/photoshop-CS6-actions-list.png)




#Action List

##Transforms:
	> 1:1 to 2:1 Aspect Ratio Expand
	> 2:1 to 1:1 Aspect Ratio Reduce
	> 50% Scale
	> 200% Scale
	> Rotate 90 Degrees
	> Rotate 180 Degrees
	> Rotate 270 Degrees
	> Flip Vertical
	> Flop Horizontal
	> Horizontal Offset 1024 pixels
	> Vertical Offset 1024 pixels
	> Horizontal and Vertical Offset 1024 pixels


##Conversions
	> Inverse Angular Fisheye
	> Angular Fisheye to Equirectangular
	> Equirectangular to Angular Fisheye
	> 3x2 to Cube Map
	> Vertical Cross to Cube Map
	> Horizontal Cross to Cube Map
	> Vertical Tee to Cube Map
	> Horizontal Tee to Cube Map
	> Vertical Strip to Cube Map
	> Horizontal Strip to Cube Map
	> Cube Map to 3x2 Cube Map
	> Cube Map to Vertical Cross
	> Cube Map to Horizontal Cross
	> Cube Map to Vertical Tee
	> Cube Map to Horizontal Tee
	> Cube Map to Vertical Strip
	> Cube Map to Horizontal Strip

	
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
	> Delete Layer Mask
	 
##General Utilities:

	> 1x6 Guide Grid
	> 3x2 Guide Grid
	> 3x4 Guide Grid
	> 4x3 Guide Grid
	> 4x4 Guide Grid
	> 6x1 Guide Grid
	> Clear Guides
	> Invert Colors
	> Background to Layer
	> Merge Visible
	> Flatten Image
	 

#Installation Instructions

The Domemaster Photoshop Actions Pack is comptaible with Photoshop CS3 to CS6 on both Mac and Windows.

##Step 1. Open the Actions Tab

Start by opening Adobe Photoshop. Navigate to the "Window" menu, and select the "Actions" menu item.

![Open the Actions Tab](https://raw.github.com/AndrewHazelden/Domemaster-Photoshop-Actions-Pack/master/Screenshots/1.install-window-actions-menu-item.png)

##Step 2. Load the actions.

Click on the Actions tab pop-up menu located at the top right of the actions tab.

Select the "Load Actions" menu item.

![Select the "Load Actions..." menu item to import the actions pack](https://raw.github.com/AndrewHazelden/Domemaster-Photoshop-Actions-Pack/master/Screenshots/2.load-actions-menu-item.png)

In the Load dialogue window select the action files "Conversions.atn", "General Utilties.atn", "Masking and Selection.atn", and "Transforms.atn".

Click the Load button to open the action files.

![Select the actions files in the Load dialogue window and click load.](https://raw.github.com/AndrewHazelden/Domemaster-Photoshop-Actions-Pack/master/Screenshots/3.load-actions-dialogue.png)

The Domemaster Photoshop Actions Pack files will be loaded into the Actions Tab.

![The Domemaster Photoshop Actions Pack is now loaded in the Actions tab.](https://raw.github.com/AndrewHazelden/Domemaster-Photoshop-Actions-Pack/master/Screenshots/4.actions-loaded.png)

##Step 3. Switch to Button Mode

If you want to make it easier to run the actions you can switch the Actions tab to "Button Mode". This will make each action item a clickable button.

Click on the Actions tab pop-up menu located at the top right of the actions tab.

Select the first item in the menu labeled "Button Mode". Your view will switch from a long list into a colorfull grid of labeled buttons.
![Switch the Actions tab to the to button display  mode](https://raw.github.com/AndrewHazelden/Domemaster-Photoshop-Actions-Pack/master/Screenshots/5.switch-to-button-mode.png)

To make it easier to find things, the actions groups are color coded:

The "Conversions" actions are blue. 

The "General Utilties" actions are violet. 

The "Masking and Selection" actions are green.

The "Transforms" actions are yellow.

![Switch the Actions tab to the to button display  mode](https://raw.github.com/AndrewHazelden/Domemaster-Photoshop-Actions-Pack/master/Screenshots/6.actions-list.png)

#Tool Descriptions

##Transforms


### 1:1 to 2:1 Aspect Ratio Expand
This action will convert a 1:1 square aspect raito image into a 2:1 aspect ratio image by scaling the document 200% larger horizontally.

### 2:1 to 1:1 Aspect Ratio Reduce
This action will convert a 2:1 square aspect raito image into a 1:1 aspect ratio image by scaling the document 50% smaller horizontally.

### 50% Scale
This action will scale the image 50% smaller using bicubic interpolation.

### 200% Scale
This action will scale the image 200% larger using bicubic interpolation.

###Rotate 90 Degrees
This action will rotate the Photoshop document by 90 degrees. This is useful for changing the orientation of the angular fisheye and equirectangular images prior to the conversion.

![Rotate 90 Degrees Example 1](https://raw.github.com/AndrewHazelden/Domemaster-Photoshop-Actions-Pack/master/Screenshots/Actions-Previews/Rotate-90-Degrees-Action.jpg)

![Rotate 90 Degrees Example 2](https://raw.github.com/AndrewHazelden/Domemaster-Photoshop-Actions-Pack/master/Screenshots/Actions-Previews/Rotate-90-Degrees-Action2.jpg)

###Rotate 180 Degrees
This action will rotate the Photoshop document by 180 degrees. This is useful for changing the up orientation of the angular fisheye and equirectangular images prior to the conversion.

![Rotate 180 Degrees Example 1](https://raw.github.com/AndrewHazelden/Domemaster-Photoshop-Actions-Pack/master/Screenshots/Actions-Previews/Rotate-180-Degrees-Action.jpg)

![Rotate 180 Degrees Example 2](https://raw.github.com/AndrewHazelden/Domemaster-Photoshop-Actions-Pack/master/Screenshots/Actions-Previews/Rotate-180-Degrees-Action2.jpg)

###Rotate 270 Degrees
This action will rotate the Photoshop document by 270 degrees. This is useful for changing the up orientation of the angular fisheye and equirectangular images prior to the conversion.

###Flip Vertical
This flips the image upside down.


###Flop Horizontal
This flops the image left and right.


###Horizontal Offset 1024 Pixels
This action slides the image 1024 pixels to the right and wraps the right side of the image around to the left side.

This is useful for changing the content in the center of an equirectangular image. This is also useful for fixing image seams and preparing tiling textures

![Horizontal Offset 1024 Pixels Example 1](https://raw.github.com/AndrewHazelden/Domemaster-Photoshop-Actions-Pack/master/Screenshots/Actions-Previews/Horizontal-Offset-1024-Pixels-Action.jpg)

![Horizontal Offset 1024 Pixels Example 2](https://raw.github.com/AndrewHazelden/Domemaster-Photoshop-Actions-Pack/master/Screenshots/Actions-Previews/Horizontal-Offset-1024-Pixels-Action2.jpg)

###Vertical Offset 1024 Pixels
This action slides the image upwards by 1024 pixels and wraps the top side of the image around to the bottom side. This is useful for fixing image seams and preparing tiling textures.

![Vertical Offset 1024 Pixels Example 1](https://raw.github.com/AndrewHazelden/Domemaster-Photoshop-Actions-Pack/master/Screenshots/Actions-Previews/Vertical-Offset-1024-Pixels-Action.jpg)

![Vertical Offset 1024 Pixels Example2](https://raw.github.com/AndrewHazelden/Domemaster-Photoshop-Actions-Pack/master/Screenshots/Actions-Previews/Vertical-Offset-1024-Pixels-Action2.jpg)

###Horizontal and Vertical Offset 1024 Pixels
This action slides the image upwards and to the right by 1024 pixels and wraps the top and right side of the image around to the bottom side. This is useful for fixing image seams and preparing tiling textures. 

If you are running this action on a 2K square resolution image it will shift the seams on an image's border to the center of the document. After you have finished your cloning or touch-up work you can run the action a 2nd time so the image border will be reset to its original position. 

On a 4K square or 8K square resolution image you will need to run the action multiple time until the seam is shifted into the center of the document.

![Horizontal and Vertical Offset 1024 Pixels Example](https://raw.github.com/AndrewHazelden/Domemaster-Photoshop-Actions-Pack/master/Screenshots/Actions-Previews/Horizontal-and-Vertical-Offset-1024-Pixels.jpg)


##Conversions

###Inverse Angular Fisheye
This action will allow you to inverse an angular fisheye image. This is the effect "rolling" the inside of the fisheye image to the outside of the frame. This effect works best with a 360&deg; degree fisheye image.

The action can be used to quickly turn a regular angular fisheye image into a "tiny planet" style image.

The inverted fisheye effect is achieved by taking your angular fisheye image and doing a polar to rectangular conversion. Then the action rotates the image 180 degrees. The final step is to convert the image from rectangular coordinates back into polar coordinates.

*Note:* It is also possible to use the "Inverse Angular Fisheye" action a 2nd time to convert a "tiny planet" image back into a normal fisheye image.

![Inverse Angular Fisheye Example](https://raw.github.com/AndrewHazelden/Domemaster-Photoshop-Actions-Pack/master/Screenshots/Actions-Previews/Inverse-Angular-Fisheye.jpg)

###Angular Fisheye to Equirectangular
This action converts a full frame fisheye image into a 360&deg; x 180&deg; spherical panorama. This is done with the help of the Photoshop polar to rectangular coordinates filter.

This action can also be used on individual alpha channels by selecting the alpha channel in the Channels tab and then clicking the button for the action.

![Angular Fisheye to Equirectangular  Example 1](https://raw.github.com/AndrewHazelden/Domemaster-Photoshop-Actions-Pack/master/Screenshots/Actions-Previews/Angular-Fisheye-to-Equirectangular-Action.jpg)

###Equirectangular to Angular Fisheye
This action converts a 360&deg; x 180&deg; spherical panorama into a full frame fisheye image. This is done with the help of the Photoshop rectangular to polar coordinates filter.

This action can also be used on individual alpha channels by selecting the alpha channel in the Channels tab and then clicking the button for the action.

![Equirectangular Panorama to Angular Fisheye Example 1](https://raw.github.com/AndrewHazelden/Domemaster-Photoshop-Actions-Pack/master/Screenshots/Actions-Previews/Equirectangular-to-Angular-Fisheye-Action.jpg)



###3x2 Cube Map to Cube Map
This converts a 3x2 cube map format image into the cubic layer map panorama format.

The converted cubic map faces are named:

<table>
	<tr>
		<td>front</td>
	</tr>
	<tr>
		<td>right</td>
	</tr>
	<tr>
		<td>back</td>
	</tr>
	<tr>
		<td>left</td>
	</tr>
	<tr>
		<td>top</td>
	</tr>
	<tr>
		<td>bottom</td>
	</tr>
</table>


###Vertical Cross to Cube Map
This converts a vertical cross format panorama into the cubic map panorama format.

The converted cubic map faces are named:

<table>
	<tr>
		<td>front</td>
	</tr>
	<tr>
		<td>right</td>
	</tr>
	<tr>
		<td>back</td>
	</tr>
	<tr>
		<td>left</td>
	</tr>
	<tr>
		<td>top</td>
	</tr>
	<tr>
		<td>bottom</td>
	</tr>
</table>

###Horizontal Cross to Cube Map
This converts a horizontal cross format panorama into the cubic map panorama format.

The converted cubic map faces are named:

<table>
	<tr>
		<td>front</td>
	</tr>
	<tr>
		<td>right</td>
	</tr>
	<tr>
		<td>back</td>
	</tr>
	<tr>
		<td>left</td>
	</tr>
	<tr>
		<td>top</td>
	</tr>
	<tr>
		<td>bottom</td>
	</tr>
</table>

###Vertical Tee to Cube Map
This converts a vertical tee format panorama into the cubic map panorama format.


The converted cubic map faces are named:

<table>
	<tr>
		<td>front</td>
	</tr>
	<tr>
		<td>right</td>
	</tr>
	<tr>
		<td>back</td>
	</tr>
	<tr>
		<td>left</td>
	</tr>
	<tr>
		<td>top</td>
	</tr>
	<tr>
		<td>bottom</td>
	</tr>
</table>


###Horizontal Tee to Cube Map
This converts a horizontal tee format panorama into the cubic map panorama format.


The converted cubic map faces are named:

<table>
	<tr>
		<td>front</td>
	</tr>
	<tr>
		<td>right</td>
	</tr>
	<tr>
		<td>back</td>
	</tr>
	<tr>
		<td>left</td>
	</tr>
	<tr>
		<td>top</td>
	</tr>
	<tr>
		<td>bottom</td>
	</tr>
</table>



###Vertical Strip to Cube Map
This converts a vertical strip format panorama into the cubic map panorama format.


The converted cubic map faces are named:

<table>
	<tr>
		<td>front</td>
	</tr>
	<tr>
		<td>right</td>
	</tr>
	<tr>
		<td>back</td>
	</tr>
	<tr>
		<td>left</td>
	</tr>
	<tr>
		<td>top</td>
	</tr>
	<tr>
		<td>bottom</td>
	</tr>
</table>

###Horizontal Strip to Cube Map
This converts a horizontal strip format panorama into the cubic map panorama format.


The converted cubic map faces are named:

<table>
	<tr>
		<td>front</td>
	</tr>
	<tr>
		<td>right</td>
	</tr>
	<tr>
		<td>back</td>
	</tr>
	<tr>
		<td>left</td>
	</tr>
	<tr>
		<td>top</td>
	</tr>
	<tr>
		<td>bottom</td>
	</tr>
</table>


###Cube Map to Vertical Cross
This converts a cube map format image into the vertical cross panorama format.

The converted vertical cross faces are located in the format:

<table>
	<tr>
		<td>blank</td> <td>top</td> <td>blank</td> <td>blank</td>
	</tr>
	<tr>
		<td>left</td> <td>front</td> <td>right</td> <td>blank</td>
	</tr>
	<tr>
		<td>blank</td> <td>bottom</td> <td>blank</td> <td>blank</td>
	</tr>
	<tr>
		<td>blank</td> <td>back (rotated 180&deg;)</td> <td>blank</td> <td>blank</td>
	</tr>
</table>


###Cube Map to Horizontal Cross
This converts a cube map format image into the horizontal cross panorama format.

The converted horizontal cross faces are located in the format:

<table>
	<tr>
		<td>blank</td> <td>top</td> <td>blank</td> <td>blank</td>
	</tr>
	<tr>
		<td>left</td> <td>front</td> <td>right</td> <td>back</td>
	</tr>
	<tr>
		<td>blank</td> <td>bottom</td> <td>blank</td> <td>blank</td>
	</tr>
</table>


###Cube Map to Vertical Tee
This converts a cube map format image into the vertical tee panorama format.

The converted vertical tee faces are located in the format:

<table>
	<tr>
		<td>left</td> <td>front</td> <td>right</td>
	</tr>
	<tr>
		 <td>blank</td> <td>bottom</td><td>blank</td>
	</tr>
	<tr>
		 <td>blank</td> <td>back (rotated 180&deg;)</td> <td>blank</td> 
	</tr>
	<tr>
		 <td>blank</td> <td>top</td> <td>blank</td>
	</tr>
</table>


###Cube Map to Horizontal Tee
This converts a cube map format image into the horizontal tee panorama format.

The converted horizontal tee faces are located in the format:

<table>
	<tr>
		<td>blank</td> <td>top</td> <td>blank</td> <td>blank</td>
	</tr>
	<tr>
		<td>front</td> <td>right</td> <td>back</td> <td>left</td>
	</tr>
	<tr>
		<td>blank</td> <td>bottom</td> <td>blank</td> <td>blank</td>
	</tr>
</table>



###Cube Map to Vertical Strip
This converts a cube map format image into a single column panorama format.

The vertical strip faces are located in the format:

<table>
	<tr>
		<td>front</td>
	</tr>
	<tr>
		<td>right</td>
	</tr>
	<tr>
		<td>back</td>
	</tr>
	<tr>
		<td>left</td>
	</tr>
	<tr>
		<td>top</td>
	</tr>
	<tr>
		<td>bottom</td>
	</tr>
</table>


###Cube Map to Horizontal Strip
This converts a cube map format image into a single row panorama format.

The horizontal strip faces are located in the format:

<table>
	<tr>
		<td>front</td> <td>right</td> <td>back</td> <td>left</td> <td>top</td> <td>bottom</td>
	</tr>
</table>




##Masking and Selection

###Crop to Selection
This action will crop the Photoshop document smaller based upon the currently selected area. The crop command will reduce the image size based upon a square cropping rectangle drawn around the current selection shape.

###Select All
This action will select all of the pixels on the current image layer.

![Select All Example](https://raw.github.com/AndrewHazelden/Domemaster-Photoshop-Actions-Pack/master/Screenshots/Actions-Previews/Select-All-Action.jpg)

###Save Selection
This action will save the current selection to a new alpha channel.

###Load Selection
This action will open the "Load Selection" dialogue. You can choose to load either a layer mask, transparency channel, or an alpha channel into the current selection region.

There are several advanced options in the the "Load Selection" dialogue that will let you do differencing operations ( new, add, subtract, intersect, or invert) your current selection.

For example of you were painting a layer mask you could change your current selection region by subtracting the shape of a mask or alpha channel from another layer or image.

###Color Range Selection
This action will load the "Color Range" dialogue. This dialogue is useful for using a color / luma keying approach to generate a new selection region.

You can preview the effects of the selection region in the dialogue or use the "Selection Preview" pop-up menu to view the results in the main Photoshop  window.


###Inside Circular 50% Mask
This action creates a circular layer mask that hides the area inside a circular region in the center of the current layer.

![Inside Circular 50% Mask Example](https://raw.github.com/AndrewHazelden/Domemaster-Photoshop-Actions-Pack/master/Screenshots/Actions-Previews/Inside-Circular-50-Percent-Mask-Action.jpg)

###Outside Circular 50% Mask
This action creates a circular layer mask that hides the area outside a circular region in the center of the current layer.

![Outside Circular 50% Mask Example](https://raw.github.com/AndrewHazelden/Domemaster-Photoshop-Actions-Pack/master/Screenshots/Actions-Previews/Outside-Circular-50-Percent-Mask-Action.jpg)


###Fisheye Alpha Channel
This action creates a full frame circular alpha channel.

A common use is to create a single circular alpha channel and then use the "load selection" action to repetitively make circular domemaster shaped boundary selections.

![Fisheye Alpha Channel Example](https://raw.github.com/AndrewHazelden/Domemaster-Photoshop-Actions-Pack/master/Screenshots/Actions-Previews/Fisheye-Alpha-Channel-Action.jpg)

###Fisheye Layer Mask
This action creates a full frame circular layer mask on the currently select layer.

To use this action you must convert all flattened background layers into floating layers. You can do this using the "Background to Layer" action.

![Fisheye Layer Mask Example](https://raw.github.com/AndrewHazelden/Domemaster-Photoshop-Actions-Pack/master/Screenshots/Actions-Previews/Fisheye-Layer-Mask-Action.jpg)

###Layer Mask From Selection
This action applies a new raster layer mask based upon the current selection. To use this action you must remove any existing "raster" layer masks from the current layer.

Layer masks are a quick and easy way to temporarily hide content on an image layer. 

![Layer Mask From Selection Example 1](https://raw.github.com/AndrewHazelden/Domemaster-Photoshop-Actions-Pack/master/Screenshots/Actions-Previews/Layer-Mask-From-Selection-Action.jpg)

![Layer Mask From Selection Example 2](https://raw.github.com/AndrewHazelden/Domemaster-Photoshop-Actions-Pack/master/Screenshots/Actions-Previews/Layer-Mask-From-Selection-Action2.jpg)

After you create a new layer mask you can edit the layer mask by opening the layers tab and clicking on the mask icon to the right of the layer icon. When the layer mask is selected you can paint the mask using the brush tool.

####Layer Mask Editing Tips
When editing a layer mask you can paint regions of the layer visible or invisible by changing the brush color to either white or black.

You can create transparent areas on the layer by using a shade of gray as the brush color when painting the layer mask.
 
If you adjust the brush hardness to 100% you can paint a crisp hard-edged matte. For a nice soft matte edge set the brush hardness to a value between 0 to 80%.

You can view the contents of a single layer mask full-screen by holding down the option key on Mac OS X or the alt key on Windows, and clicking on a layer mask thumbnail image in the Layers Tab. 

To exit the full-screen layer mask view you need to click back on the layer's color thumbnail image in the Layers Tab.

You can invert a layer mask by selecting the layer mask thumbnail icon and clicking the "Invert Colors" action button. This will reverse the visible and hidden areas in the layer mask.

###Layer Mask From Inverse Selection
This action creates a new layer mask based upon inverting the current selection. To use this action you must remove any existing "raster" layer masks from the current layer.

![Layer Mask From Inverse Selection Example 1](https://raw.github.com/AndrewHazelden/Domemaster-Photoshop-Actions-Pack/master/Screenshots/Actions-Previews/Layer-Mask-From-Inverse-Selection-Action.jpg)

![Layer Mask From Inverse Selection Example 2](https://raw.github.com/AndrewHazelden/Domemaster-Photoshop-Actions-Pack/master/Screenshots/Actions-Previews/Layer-Mask-From-Inverse-Selection-Action2.jpg)


###Enable Layer Mask
This action will enable the layer mask on the current layer. This is useful for comparing the effects of transparency on the current layer.

![Enable Layer Mask Example](https://raw.github.com/AndrewHazelden/Domemaster-Photoshop-Actions-Pack/master/Screenshots/Actions-Previews/Enable-Layer-Mask-Action.jpg)


###Disable Layer Mask
This action temporarily disables the layer mask on the current layer. This is useful for comparing the effects of transparency on the current layer.

![Disable Layer Mask Example](https://raw.github.com/AndrewHazelden/Domemaster-Photoshop-Actions-Pack/master/Screenshots/Actions-Previews/Disable-Layer-Mask-Action.jpg)

###Delete Layer Mask
This action deletes the layer mask on the current layer.

![Delete Layer Mask Example](https://raw.github.com/AndrewHazelden/Domemaster-Photoshop-Actions-Pack/master/Screenshots/Actions-Previews/Delete-Layer-Mask-Action.jpg)



##General Utilities

###1x6 Guide Grid
This creates a vertical strip style 1x6 alignment guide layout. This grid is extremely useful for making accurate selections in the image when the "Snap to Guides" command is turned on.

###3x2 Guide Grid
This creates a 3x2 cube map style alignment guide layout. This grid is extremely useful for making accurate selections in the image when the "Snap to Guides" command is turned on.

###3x4 Guide Grid
This creates a vertical cross or vertical tee style 3x4 alignment guide layout. This grid is extremely useful for making accurate selections in the image when the "Snap to Guides" command is turned on.

###4x3 Guide Grid
This creates a horizontal cross or horizontal tee style 4x3 alignment guide layout. This grid is extremely useful for making accurate selections in the image when the "Snap to Guides" command is turned on.

###4x4 Grid Guide
This action creates a 4x4 style alignment guide layout. This grid is extremely useful for making accurate selections in the image when the "Snap to Guides" command is turned on. You can use the grid to make sure the nadir point in the fulldome image is perfect centered.

![4 x 4 Grid Guide Example](https://raw.github.com/AndrewHazelden/Domemaster-Photoshop-Actions-Pack/master/Screenshots/Actions-Previews/4-x-4-Grid-Guide-Action.jpg)

![4 x 4 Grid Guide Example](https://raw.github.com/AndrewHazelden/Domemaster-Photoshop-Actions-Pack/master/Screenshots/Actions-Previews/4-x-4-Grid-Guide-Action2.jpg)

###6x1 Guide Grid
This creates a horizontal strip style 6x1 alignment guide layout. This grid is extremely useful for making accurate selections in the image when the "Snap to Guides" command is turned on.

###Clear Guides
This action will remove all of the guides from the current Photoshop document.

![Clear Guides Example](https://raw.github.com/AndrewHazelden/Domemaster-Photoshop-Actions-Pack/master/Screenshots/Actions-Previews/Clear-Guides-Action.jpg)

###Invert Colors
This action will invert the image colors of the currently selected layer. This action can be used on color images, layer masks, and alpha channels.

![Invert Colors Example](https://raw.github.com/AndrewHazelden/Domemaster-Photoshop-Actions-Pack/master/Screenshots/Actions-Previews/Invert-Colors-Action.jpg)

My favorite use of this filter is to invert a grayscale layer mask. This will reverse the visible and hidden parts of the layer mask. 

This action can be used on individual alpha channels by selecting the alpha channel in the Channels tab and then clicking the button for the action. The action can also used on a layer mask by selecting the layer mask's thumbnail icon in the layers tab and then clicking the button for the action.

###Background to Layer
This action will convert a flattened image from the background layer mode into a floating layer that supports features like layer masks.

The most common use for this action is to prepare an imported picture like a flat JPEG .jpg or Targa .tga file for custom layer masks.

![Background to Layer Example](https://raw.github.com/AndrewHazelden/Domemaster-Photoshop-Actions-Pack/master/Screenshots/Actions-Previews/Background-to-Layer-Action.jpg)

###Merge Visible
This action will merge all of the visible layers into a single layer. 

This action is different than the flatten image command in that it will ignore any hidden layers. You can use the merge visible command to selectively flatten layers by hiding the other layers, elements, and groups you want to keep.

This version of Merge Visible can merge a single layer and bake the layer mask and layer style effects into the final image.

###Flatten Image
This action will merge all of the layers in the current Photoshop document. This is useful for removing transparency from an image, merging layer style effects, vector shapes, and editable text layers into a single raster image.

When an image is flattened, all of the transparent background areas in the image will be filled with a solid color.

*Note:* You really want to have saved a backup of your Photoshop document before you flatten the image because all of your layers are permanently merged into a single element!


* * *

Actions Created by Andrew Hazelden. (c) copyright 2012.

Email: andrew@andrewhazelden.com

Blog: http://www.andrewhazelden.com
