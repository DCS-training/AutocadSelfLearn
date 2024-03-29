# Lesson 2
## What will you learn in this lesson?
__Lesson 2__
1. Setting up your drawing
2. Annotations
3. Styling & Hatches
4. Updating information and practising commands in modifying objects in your drawing
5. Exporting your drawing

## 1. Setting up your drawing
Well done at getting the table drafted. The front, side, and bottom views of the desk are now available. It's time to communicate the key information to your audience. There are typically, three types of information we need to communicate for any standard CAD drawings, they are, 
* Dimensions (use of dimensions annotations)
* Materials and details (use of text box)
* Title block (scale, revision, authors, date of issue, etc)
Let's learn how to add each type of information one by one.

### Dimensions (use of dimensions annotations)
To label the width and the length of your drawing, you will need to activate the dimension command (DI). Alternatively, you could access the function by clicking on annotate $\\rightarrow$ drop-down arrow next to linear $\\rightarrow$ select aligned. 

![](https://github.com/ktonguk/autocad/blob/main/lesson2/image/03_dimension.gif)

(In general, aligned dimensions are better than linear dimensions because linear must be annotations along either the x or y axis whereas aligned dimensions allow you to label objects at an angle. As you have noticed in the dropdown menu, you could also annotate other geometries, such as angle and radius. please do try them out with your drawing although they won't be covered in the current course.)

After selecting the aligned dimension, click on the first point and then the last point to indicate the dimension of the object you would like to label. 

![](https://github.com/ktonguk/autocad/blob/main/lesson2/image/04_aligned_dimension.gif)

### Dimension style manager
If the text appears too small to you, you could adjust the style of the annotation. To do that, click on the small arrow at the bottom right-hand corner of the dimension panel $\\rightarrow$ and select the style that has been activated in the dimensions window. (The pre-set should be "annotative"). $\\rightarrow$ choose modify $\\rightarrow$ select text tab $\\rightarrow$ increase text size (e.g. 5.0 instead of 2.5, that means doubling the original size) $\\rightarrow$ press ok to execute the change.

![](https://github.com/ktonguk/autocad/blob/main/lesson2/image/05_dimension_style_manager.png)
![](https://github.com/ktonguk/autocad/blob/main/lesson2/image/06_textsize.png)

Now you are all set with the dimensions. Let's try adding annotated text to the drawing.

### Leader
Annotated text can be added as leaders to the drawing. Go to the annotate tab $\\rightarrow$ click on multileader $\\rightarrow$ click to set the first point (where the arrow of the annotated text points at) $\\rightarrow$ click to set the endpoint (that determines the length of the leader) $\\rightarrow$ type some text as place holder (you can change later) $\\rightarrow$ click on the blank space outside the text box to confirm with changes.

![](https://github.com/ktonguk/autocad/blob/main/lesson2/image/07_leader.gif)

You will notice the size of the leader is a bit small overall. You could customise the size by yourself using the same technique introduced above for dimensions, or, change the style from Standard to Annotative. 

![](https://github.com/ktonguk/autocad/blob/main/lesson2/image/08_annotative.gif)

Make sure the annotative mode is on for the leader before you change the style. You can access the panel as shown below by typing Properties $\\rightarrow$ into the command bar. 

![](https://github.com/ktonguk/autocad/blob/main/lesson2/image/09_annotative_properties.png)

Let's try annotating the key dimensions on your own based on what you have just learnt!

As the amount of information increases, the more you need to pay attention to the organisation of the drawing. As a rule of thumb, information of the same kind should be assigned to the same __layer__ in AutoCAD. 

#### Layer 
Type layer $\\rightarrow$ space into the command bar. A pop-up menu will come up like the following,

![](https://github.com/ktonguk/autocad/blob/main/lesson2/image/01_layer.png)

Alternatively, you could access it by double-clicking on layer properties in the middle of the ribbon.

![](https://github.com/ktonguk/autocad/blob/main/lesson2/image/02_layer_ribbon.png)

There should only be one layer at the moment. All lines should be within the 0 layer. To organise your drawing, it's good practice to keep all the annotations in one layer. Therefore, please add a new layer in the panel. To do this, click on the icon with a star $\\rightarrow$ name the layer as annotation $\\rightarrow$ enter once you are done.

![](https://github.com/ktonguk/autocad/blob/main/lesson2/image/10_newlayer.gif)

Next is to assign information to the annotation layer. To that, select the annotations you have created $\\rightarrow$ click on the dropdown menu at the centre of the ribbon $\\rightarrow$ and select the annotation layer. You should be able to see a change in colour if you have set it up correctly. 

![](https://github.com/ktonguk/autocad/blob/main/lesson2/image/02_layer_ribbon.gif)








