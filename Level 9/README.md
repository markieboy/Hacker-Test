# Level 9

![Alt text](level9.PNG?raw=true)

#
### SOLUTION
 
### Right click on the web page to "View Page Source"
	
	<HTML>
	<HEAD>
	<base href='http://www.hackertest.net/'>
	</HEAD>
	<BODY BGCOLOR="ffffff" TEXT="000000" BG="images/phat.gif">
	<!-- SOURCE CODE IS NOT AVAILABLE AT THIS TIME //-->

> On first glance the source code does not appear to say anything interesting.

> However, notice that you can scroll further down the page source.

> On line 706 a bunch more source code is evident, but still tells you little.

> Scroll down to line 1054 to see the start of a comment statement `<!-----------`

> Scroll along this statement reveals `Password: Z2F6ZWJydWg= add a page extention to that`.

> This password `Z2F6ZWJydWg=` is base64 encoded.

> Open a base64 decoder such as www.base64decode.org/, and decode the password as `gazebruh`.

### Next level: http://www.hackertest.net/gazebruh.php
