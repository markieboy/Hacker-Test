# Level 3

![Alt text](level3.PNG?raw=true)

#
### SOLUTION
 
### Click on the "OK" button to send a blank password and remove the pop up from the screen.
### With the pop up removed you can right click on the web page to "View Page Source".

	<body onload=javascript:pass(); alink="#000000">
	<SCRIPT LANGUAGE="JavaScript">
	function pass()
	{
	var pw, Eingabe;
	pw=window.document.alinkColor;
	Eingabe=prompt ("Please enter password");
	if (Eingabe==pw)
	{
	window.location.href=String.fromCharCode(97,98,114,97,101)+".htm";
	}
	else
	{
	alert("Try again");
	}
	}
	</SCRIPT>

> The password `pw` is `window.document.alinkColor`. A few lines higher up the alink colour is set to `alink="#000000"`.

### Enter “#000000” as the password.

#
There is an alternative solution for this level

> In the Javascri statement `window.location.href=String.fromCharCode(97,98,114,97,101)+".htm";`, part of the next level URL is encoded in ASCII. 

> ASCII(97) is `a`, ASCII(98) is `b`, ASCII(114) is `r`, ASCII(97) is `a` and ASCII(101) is `e`.

### Enter the URL www.hackertest.net/abrae.htm to go to the next level.

### Next solution: [Level 4](/Level%204/)
