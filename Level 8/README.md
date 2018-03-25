# Level 8

![Alt text](level8.PNG?raw=true)

#
### SOLUTION
 
### Right click on the web page to "View Page Source"

	<tr>
	<td width="100%" height="10">
	<form action=phat.php method=post>

> The page source makes reference to `action=phat.php`.

> Click on the phat.php link reveals more HTML:

	<HTML>
	<HEAD>
	<base href='http://www.hackertest.net/'>
	</HEAD>
	<BODY BGCOLOR="ffffff" TEXT="000000" BG="images/phat.gif">
	<br><br><p align=center><b>Authentication Failed. Try again.</b></BODY>
	</HTML>

> This HTML refers to `images/phat.gif`.

> In a new browser tab open www.hackertest.net/images/phat.gif

> At the bottom of this image it says `Look for a Photoshop Document!`

> Change the browser to www.hackertest.net/images/phat.psd

> Download the image and open in it at: https://www.ofoct.com/viewer/psd-viewer-online.html

> This website shows the different layers in the .psd file. 

> One layer says `login: zadmin pass: stebbins`

### Enter “zadmin” as the username. The password is not needed.

### Next level: http://www.hackertest.net/phat.php

### Next solution: [Level 9](/Level%209/)
