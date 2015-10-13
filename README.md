## «Modulizer»

Modulizer plug-in for [Sketch.app](http://bohemiancoding.com/sketch/) allows you easy control paddings for buttons, modules and areas. If your module has background your can set fixed paddings and easy restore it for any content changes.

Use cases:
* Merge selection to group and save the paddings in bottom background layer
* Restore paddings after content changing
* Change paddings value on bg layer name and update it's



## Demo

[![Demo Video](https://dl.dropboxusercontent.com/u/3240668/sketch/ModulizerVideo.png)](http://youtu.be/7ZHsr-dmHHM)

## How to use:

1. **Create a background element**: Draw a rectangle<a href="#rectangle"><sup>1</sup></a> for your background element. 

2. **Create your content**: Content can be a single element (like a text box) or a group of elements. (Text boxes, rectangles, or any other group of elements.)

3. **Run the Plugin**: cmd + shift + m

4. **Enter your settings**: The window accepts pixel values in the <a href="#css-order">same order as css</a>.

5. **Modifying settings**: ctrl + cmd + shift + m lets you set new values. Alternatively, you can rename the layer with your desired padding and rerun cmd + shift + m.

<sup name="rectangle">1</sup> You can also use an ellipse, but it doesn't work well with a perfect circle on a rectangular element. For most consistent results, use a rectangle.

## CSS order

<a name="css-order"></a>Enter in your values in the order of **Top**, **Right**, **Bottom**, **Left**. 

* Entering 1 value will cause all padding to be the same (e.g. "10" for 10px of padding on all sides)
* Entering 2 values will apply the first value to **Top** and **Bottom**, and the second value to **Right** and **Left** (e.g. "10 20" would be the same as entering "10 20 10 20")
* Entering 3 values will set unique **Top** and **Bottom** values, but identical **Right** and **Left** values. (e.g. "10 20 30" would be the same as entering "10 20 30 20")

© 2014 Falkeyn: [Twitter](https://twitter.com/falkeyn) and [Facebook](https://www.facebook.com/Falkeyn)
