# Slice Manager

Slice Manager is an Aseprite script for managing large amount of slices quickly

<br />

**Changelog:**

+ v1.0: Initial release
<br />

## Main features ##

+ Rename, renumber, recolor multiple slices  
+ Remove multiple slices or clear all slices
+ Export multiple slices

+ Works alongside [BETTER SLICER](https://github.com/ngndang/Better-Slicer) - a script I made for automatically creating slices

## How to use ##

![image](https://user-images.githubusercontent.com/78392599/140313628-b8097a57-053a-4194-a887-af1df0ba4817.png)


============= Modifying Slices =============

![image](https://user-images.githubusercontent.com/78392599/140304559-0878b3de-cf23-4f55-a343-13b2e81a551a.png)

The naming format is: *name_number*

1. *Rename* will change the *name* of all slices inside your selection with the name you put in the box
2. *Renumber* will go through the slices only inside your rectangle selection and *number* them from 0 up. You don't have to input anything for this
3. *Recolor* will change the color of all slices inside your selection with the color you selected
4. *Reapply* will change all of the above for slices inside your selection

**Note**
+ Make sure to make your selection a rectangle and contains the whole slice
+ The renumber will go through slices that is in the most upper left position, with the pivot being in the upper left, so the slice in red will appear first, and numbered smaller. So if you have a large project make sure to align the slices beforehand.

![image](https://user-images.githubusercontent.com/78392599/140306099-9d82392a-c21e-4ef2-b295-3f04067a804b.png)


============= Deleting Slices =============

![image](https://user-images.githubusercontent.com/78392599/140306442-022acd92-e315-4811-b56a-b85c76091a44.png)

Removing slices inside of your selection or all slices on the canvas. 

>Don't worry it is undoable, if you happen to miss click

============= Exporting Slices =============

![image](https://user-images.githubusercontent.com/78392599/140306816-69c25288-5c0f-4f7a-bfbb-0e96ff602afe.png)

Export slices inside of your selection or all slices on the canvas.

You can also change the scale and file output directory

**Note**
+ Currently supported file types are: .png, .jpg, .svg
+ By default the script will create a subfolder named *filename_Slices* in the same folder as the active file
+ The *Add sprite name as prefix option* will give files named *filename_slicename_number.extension* 

>*Updating*
