# Blender Add-on to Render Text Using Stroke Fonts
This add-on allows the user to render text using stroke font. Stroke fonts have glyphs that can have open paths, so they can be used e.g. in writing animation. The add-on comes bundled with a set of 26 stroke fonts.<br>
Supported Blender version: 2.8 beta (please make sure you have a build downloaded after April 15, 2019)<br>

# Installation
- Download addstrokefont_2_8.zip, open Blender and select File->User Preferences <br>
- Click install Add-ons tab and then Install Add-on from File<br>
- Select the downloaded file <br>
- Check the 'Add Stroke Font Text' option in the add-ons dialog <br>

After installation, a new 'Add Stroke Font Text' panel is displayed in 'Active Tool and Workspace settings' area when Blender is in object mode.<br>

# Quick start
Select 'Add Input Text' option in the 'Action' drop-down, input the text to be rendered in the text box, select the font and click 'Add Stroke Font Text'. To render text from a file choose 'Add Text from File' action. <br>
With 'Confine Area' checkbox selected, you can choose horizontal and vertical alignment for text rendering. <br><br>
When the <b>Clone Glyphs</b> option is selected, all glyphs pertaining to the same characters share the data block.
![Demo](https://github.com/Shriinivas/blenderstrokefont/blob/master/cloneglyphs.gif)

# Video Tutorial
<a href=https://youtu.be/whysGoZPXt8> The introductory video</a> provides a detailed overview of the add-on functionality<br>
There is also a <a href=https://youtu.be/IF6r7mp7IN0>demo video</a> about the various options available.<br>

# Credits
The custom stroke fonts are derived from: Square Grotesk and Pinyon Script available under Open Font License on https://fontlibrary.org/<br><br>
The data of Hershey Fonts is ported from Hershey Text Inkscape Extension (hersheydata.py) from Windell H. Oskay.<br>
Here's the acknowledgement:
- The Hershey Fonts were originally created by Dr. A. V. Hershey while working at the U. S. National Bureau of Standards.
- The format of the Font data in this distribution was originally created by<br>
James Hurt<br>
Cognition, Inc.<br>
900 Technology Park Drive<br>
Billerica, MA 01821<br>
(mit-eddie!ci-dandelion!hurt)<br>

The add-on includes python converted <a href=https://github.com/fontello/svgpath>a2c</a> js function (Copyright (C) 2013-2015 by Vitaly Puzrin)
and SVG parser imported from <a href=https://github.com/mathandy/svgpathtools>svgpathtools</a> (Copyright (c) 2015 Andrew Allan Port, Copyright (c) 2013-2014 Lennart Regebro)<br>

# Limitations
<b>Creating Custom Fonts</b>
This add-on does not support stroke font creation. However, I have published a set of Inkscape extensions for creating and editing stroke fonts. Here are the related video tutorials:<br>
Part1: https://youtu.be/iCsnYlVjWA0 <br>
Part2: https://youtu.be/-7BjfxpUAfU <br>
Part3: https://youtu.be/3YBaZfPpNjc <br>

<b>Known Issues<br></b>
If you undo the add text operation, the eye dropper selections made previously in 'Properties of' option may not function consistently. So after undoing, even if this option shows a non-blank object, you will have to select the corresponding object once again (if there was a selection before undoing).<br>

<b>The tool is in alpha stage, so please exercise caution while using it; save your work, before invoking the add-on. </b><br>
You may report the issues and defects on the Issues page here or in the comments section on the video tutorial.<br>
Feedback and suggestions are most welcome!


