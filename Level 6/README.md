# Level 1

![Alt text](level1.PNG?raw=true)

#
### SOLUTION
 
### Right click on the web page to "View Page Source"

	</script>
	</head>
	<body onLoad=password()>
	<script language=JavaScript>
	{
	var a="null";
	function check()
	{
	if (document.a.c.value == a)
	{
	document.location.href="http://www.hackertest.net/"+document.a.c.value+".htm";
	}
	else
	{
	alert ("Try again");
	}
	}
	}
	</script>

> The if statement `if (document.a.c.value ==a)` checks to compare if the user-entered password is equal to `var a`

> Two lines above this `var a` is set to “null”

### Enter “null” as the password.

### Next level: www.hackertest.net/null.htm
