recursive menu wheel - heatmap commandslike NCIS tv serie...using thjit.org tools 
combination for recursive rendering and filtering of an  xml database.

Objective is obtain an incredibly fast interface to modify input and output on the fly

some starting points:
example of XmlDb  I wish use eXist xmldb,  default configuration to make it the simplest possible.
http://exist.sourceforge.net/

thejit.org menu wheel command, with example code !
http://thejit.org/static/v20/Jit/Examples/Sunburst/example2.html

thejit.org heatmap , with example code !
http://thejit.org/static/v20/Jit/Examples/Treemap/example1.html


--------------------
Process example:
xmldb table is rendered as webpage by thejit.org heatmap
Click on a colored box
make the command wheel appears (menu containing commands)

choose a command from wheel and click it - 
wheel menu sends url containing query

Command get executed and being itself a query (every command is a click url) http://..../.xql

then some box in heatmap change(shape and colors, names etc.)
which also filter the possible menus available on the next wheel because

if now select a box and box is red then possible wheel commands are url1, url2,url3,url4
and wheel executes (click url) command url3. 

..wait for query output..
new map shows other boxes
now click on a red box...

command wheel appears and possible commands are url2,url3
(click url) and wheel executes  command url2. 

-------------
This is what i had in mind- please you go on from here...
-if i do all the juice there is no fun.