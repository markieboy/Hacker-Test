# Level 6

![Alt text](level6.PNG?raw=true)

#
### SOLUTION
 
### Click on the "OK" button to send a blank password and remove the pop up from the screen.
### With the pop up removed you can right click on the web page to "View Page Source".

	<h1>Level 6</h1>
	<SCRIPT SRC="psswd.js" LANGUAGE="JavaScript" type="text/javascript"></script>

> The Javascript points to a file `psswd.js`.

> Click on this to examine the .js file:

	<!--
	var pass;
	pass=prompt("Password:","");
	if (pass=="hackertestz") {
	window.location="included.htm";
	}else 
	alert("Try again...");
	//-->

> If if statement `if (pass=="hackertestz")` shows the password.

### Enter “hackertestz” as the password.

#
There is an alternative solution for this level

> In the Javascri statement the next level url is shown as `window.location="included.htm";`.

### Next level: www.hackertest.net/included.htm
