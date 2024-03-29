# Lesson 2
## What will you learn in this lesson?
__Lesson 2__
1. Overview of setting up your drawing
2. Annotations
3. Setting up the PDF for exporting your drawing
4. Styling & Hatches
5. Exporting your drawing

## 1. Overview of setting up your drawing
Well done at getting the table drafted. For those who would like to join only lesson 2 but not lesson 1, Table-lesson2.dwg is available in the folder for you to download, which has all tasks from lesson 1 completed. The front, side, and bottom views of the desk are now available. It's time to communicate the key information to your audience. There are typically, three types of information we need to communicate for any standard CAD drawings, they are, 
* Dimensions (use of dimensions annotations)
* Materials and details (use of text box)
* Title block (scale, revision, authors, date of issue)
Let's learn how to add each type of information one by one.

## 2. Annotations
### Dimensions (use of dimensions annotations)
To label the width and the length of your drawing, you will need to activate the dimension command (DI). Alternatively, you could access the function by clicking on annotate $\\rightarrow$ drop-down arrow next to linear $\\rightarrow$ select aligned. 

![](https://github.com/ktonguk/autocad/blob/main/lesson2/image/03_dimension.gif)

(In general, aligned dimensions are better than linear dimensions because linear must be annotations along either the x or y axis whereas aligned dimensions allow you to label objects at an angle. As you have noticed in the dropdown menu, you could also annotate other geometries, such as angle and radius. please do try them out with your drawing although they won't be covered in the current course.)

After selecting the aligned dimension, click on the first point and then the last point to indicate the dimension of the object you would like to label. 

![](https://github.com/ktonguk/autocad/blob/main/lesson2/image/04_aligned_dimension.gif)

#### Dimension style manager
If the text appears too small to you, you could adjust the style of the annotation. To do that, click on the small arrow at the bottom right-hand corner of the dimension panel $\\rightarrow$ and select the style that has been activated in the dimensions window. (The pre-set should be "annotative"). $\\rightarrow$ choose modify $\\rightarrow$ select text tab $\\rightarrow$ increase text size (e.g. 5.0 instead of 2.5, that means doubling the original size) $\\rightarrow$ press ok to execute the change.

![](https://github.com/ktonguk/autocad/blob/main/lesson2/image/05_dimension_style_manager.png)
![](https://github.com/ktonguk/autocad/blob/main/lesson2/image/06_textsize.png)

Now you are all set with the dimensions. Let's try adding annotated text to the drawing.

### Materials and details (use of text box)
#### Leader
Annotated text can be added as leaders to the drawing. This is typically useful when you are trying to add in information such as the material of the object or instructions for assembly that provide information additional to the graphical contents. To do that, go to the annotate tab $\\rightarrow$ click on multileader $\\rightarrow$ click to set the first point (where the arrow of the annotated text points at) $\\rightarrow$ click to set the endpoint (that determines the length of the leader) $\\rightarrow$ type some text as place holder (you can change later) $\\rightarrow$ click on the blank space outside the text box to confirm with changes.

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

![](https://github.com/ktonguk/autocad/blob/main/lesson2/image/02_assign.gif)

Perfect! Now you have got the basic knowledge to set up a drawing with information organised.

### Title block (scale, revision, authors, date of issue)
The final type of information that you typically will need to communicate is the information of the drawing itself. For instance, who was responsible for drawing it? When was it last issued/ updated? What's the scale of the drawing? However, it could be quite time-consuming to set up from scratch a clean format to present the text-based information. Luckily, you have got a template available in the folder, which is called "Title Block.dwg". Let's open it and take a look.

![](https://github.com/ktonguk/autocad/blob/main/lesson2/image/11_titleblock.png)

Nice, you have got a template for the title block. The issue is now you have two drawings. You would like to insert all lines of the title block into the table drawing. However, you would like to separate the lines for the title block as one object and the other lines in the table drawing on its own. In this case, you could organise your title block template lines as one block, and then insert the block into the table drawing. Let's go through the block command step by step. 

#### Block (B)
Select all lines in the title block template drawing, then type block or B $\\rightarrow$ space. Type title block as its name. Keep everything else as the default setting $\\rightarrow$ press ok $\\rightarrow$ specify the insertion point (typically the corner of the title block as reference for inserting into a new drawing)

![](https://github.com/ktonguk/autocad/blob/main/lesson2/image/12_block.gif)

Now you have created the block. Next is to bring that into your table drawing. 

## 3. Setting up the PDF for exporting your drawing
Before we can bring in the title block, we first have to set up a layout for exporting your drawing as a PDF. AutoCAD comes with a pre-set layout called Layout 1, which can be accessed by clicking on the tab at the bottom left-hand corner. 

![](https://github.com/ktonguk/autocad/blob/main/lesson2/image/13_newlayout.gif)

This is the paper space of AutoCAD. Anything to do with the paper space is related to the information to be exported. One issue with the current view is that you have no idea about the paper size. We need to check if the paper size is what we are after. To do that, go to the layout tab $\\rightarrow$ Page Setup $\\rightarrow$ the Page Setup Manager will pop up. Then choose "Layout 1" and click "Modify". 

Once you are inside Page Setup, set Name: Dwg To PDF (Dwg To PDF is preferred, which optimises the file size), then set paper size to be A3 (ISO full bleed A3 420.00 x 297.00mm). You could customise these settings depending on the need of the drawing. For the time being, the set-up is suggested to cover the extent of the drawing you have created. Once ready, please click OK. 

![](https://github.com/ktonguk/autocad/blob/main/lesson2/image/14_layoutmanager.gif)

You will notice the __viewport__ showing the extent of the drawing is too small compared with the paper space. There we need to enlarge the extent of the viewport. This is intuitive, you just have to pull the corners to fit!

![](https://github.com/ktonguk/autocad/blob/main/lesson2/image/15_viewport.gif)

Interesting, only the viewport has changed but not the size of the drawing! How can I make the drawing fit the frame then? To do that, double-click into the viewport to enter the viewport space $\\rightarrow$ type z (to activate the zoom function)  $\\rightarrow$ space  $\\rightarrow$ type sc (to activate the scale function)  $\\rightarrow$ space  $\\rightarrow$ type 1/10XP (this indicates it's a scale of 1:10) $\\rightarrow$ space. The drawing should now zoom in to the scale you which you used for drafting the model. However, the drawing is not centred. To centre it, type Pan/ P $\\rightarrow$ space $\\rightarrow$ and move the drawing to centre it (please ensure you don't accidentally hit the roller of your mouse which will then change the scale!). Once you are done, press Esc and then double-click on the grey area outside the paper space to jump out of the viewport. 

![](https://github.com/ktonguk/autocad/blob/main/lesson2/image/16_zoomview.gif)

Lastly, bring your title block in. To do that, go to the title block template drawing, copy (crtl + c) the block, and then go back to the table drawing to paste (crtl + v) the title block into layout 1. Place the title block to fit within the paper space. You might have the title block slightly covering the tables. To make sure the whole drawing shows, double-click into the viewport to activate the viewport $\\rightarrow$ Pan or P $\\rightarrow$ space $\\rightarrow$ move the drawing to ensure everything shows $\\rightarrow$ Esc $\\rightarrow$ double-click on the grey area outside the paper space to jump out of the viewport. 

![](https://github.com/ktonguk/autocad/blob/main/lesson2/image/17_copyandpaste.gif)

Yeah! You have got your PDF set up for export and it's looking very good. Let's go back to the model space to do the icing.

## 4. Styling & Hatches
#### Styling your lines
You can change the style (colour and line type) of your linework in layer properties. You have learnt how to change the colour for the annotations in the earlier part of the tutorial, let's try changing the line thickness of the layer. To do that, double-click layer properties $\\rightarrow$ go to Lineweight and change Default to 2.00mm.

![](https://github.com/ktonguk/autocad/blob/main/lesson2/image/18_lineweight.gif)

You will notice that nothing has changed. This is because AutoCAD has not been switched to display lineweights. To ensure the software to display the lineweights, enter lineweight into the command bar $\\rightarrow$ space $\\rightarrow$ check display lineweight $\\rightarrow$ OK. Now, see if your drawing has very thick lines in the model space.

![](https://github.com/ktonguk/autocad/blob/main/lesson2/image/19_display_lineweight.gif)

Wow, too thick. 2.00mm doesn't work, let's undo and change lineweight to 0.20mm in layer properties. 
You will notice there are other styling options you could play around with such as the linetype. Please have a go and explore how to style your drawing.

### Styling with hatches
You can add a solid colour/ gradient/ pre-installed texture in AutoCAD to make your drawing more realistic to help your audience understand, for instance, the material you are using for the table. To assign a solid colour/ gradient/ pre-installed texture to an object, you will use the hatch function. 

There are two ways to hatch an object:
* Hatch by filling the interior of an object.
* Hatch by selecting a polyline which forms the outline geometry of the object you want to hatch.
Let's draw two rectangles to see how they work.

#### Hatching by filling the interior
Enter Hatch or H $\\rightarrow$ space $\\rightarrow$ type K (which means pic__k__ points) $\\rightarrow$ space click into the centre of the rectangle to fill the object. 

![](https://github.com/ktonguk/autocad/blob/main/lesson2/image/20_hatch_k.gif)

#### Hatching by selecting a polyline which forms the outline geometry of the object you want to hatch.
Enter Hatch or H $\\rightarrow$ space $\\rightarrow$ type s (which means __select__ objects) $\\rightarrow$ space click on the edge of the rectangle to fill the object.

![](https://github.com/ktonguk/autocad/blob/main/lesson2/image/20_hatch_s.gif)

#### Hatching a solid
How to change the hatch to a solid fill? To do that, click onto the hatch you have just created, in the pattern window, select solid. 

![](https://github.com/ktonguk/autocad/blob/main/lesson2/image/20_hatch_solid.gif)

You could further change the colour by changing the setting from layer to a colour that best represents the colour you want. 

![](https://github.com/ktonguk/autocad/blob/main/lesson2/image/20_hatch_solid_colour.gif)

#### Hatching other patterns
There are many other patterns that you could use in AutoCAD, click on the arrow at the bottom right-hand corner of the pattern window to explore what else you could play with!

![](https://github.com/ktonguk/autocad/blob/main/lesson2/image/20_hatch_other_pattern.gif)

Sometimes, the scale of the pattern might be too big or too small. Therefore, you will need to adjust the scale accordingly, to change the scale, change the value of the text box at the bottom right hand corner under properties until you are happy!

![](https://github.com/ktonguk/autocad/blob/main/lesson2/image/21_hatch_scale.gif)

Now, let's style your table with some colours and/ or textures!

## 5. Exporting your drawing (Finally, time to export, well done at staying with us!
Now everything is good to go. Let's learn how to export your drawing as a pdf. The most common method to export as a print-out is the pdf, which is the most stable option. Let’s go to Layout 1 which you have just created. Click on Plot. 

![](https://github.com/ktonguk/autocad/blob/main/lesson2/image/22_export.png)

Then a pop-up window will show. The details should be the same as the settings you did when setting up the layout. Now press ok $\\rightarrow$ choose where to save $\\rightarrow$ press save. 

Tada~ your first CAD drawing is ready to share. 

## Thank you!
This is the end of the two short lessons on learning the fundamentals of drafting with AutoCAD. Hope you have learnt something useful and could bring it on to use in other aspects of life. All the best to your journey with the software. Thank you for learning with us!

