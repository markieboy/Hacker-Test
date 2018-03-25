# Level 13

![Alt text](Level13.PNG?raw=true)

#
### SOLUTION
 
### Right click on the web page to "View Page Source"

	...
	<meta name="clue" content="use graphic software">
	...
	<td width="100%" height="267" valign="top"><b><font size="7" face="Arial">
	<img src="images/lvl13.gif"></font></b><p>&nbsp;</p>
	...
	
> Right near the start of the source code is a clue `<meta name="clue" content="use graphic software"`.

> Lower down in the source code is hidden a .gif image `<img src="images/lvl13.gif">`.

> Download this .gif file and open in a image editor such as GIMP.

> Zoom into the image, and across lower case "l" is written `4.xml`

### Open the URL: http://www.hackertest.net/4.xml
	...
	<Worksheet ss:Name="Sheet1">
	<Table ss:ExpandedColumnCount="20" ss:ExpandedRowCount="54" x:FullColumns="1" x:FullRows="1">
	<Row ss:Index="54">
	<Cell ss:Index="20">
	<Data ss:Type="String">4xml.php</Data>
	</Cell>
	...

> In this XML code you see a data string `4xml.php`.

### Next level: http://www.hackertest.net/4xml.php
