# Level 2

image

#
### SOLUTION

### Click on the "OK" button to send a blank password and remove the pop up from the screen.
### With the pop up removed you can right click on the web page to "View Page Source".

	</head>
	<body>
	<script language="JavaScript" type="text/javascript">
	var pass, i;
	pass=prompt("Please enter password!","");
	if (pass=="l3l") {
	window.location.href="http://www.hackertest.net/"+pass+".htm";
	i=4;
	}
	</script>

> The if statement declares that `if (pass=="l3l)`, then l3l is added to the href link to the next level `href="http://www.hackertest.net/"+pass+".htm"`

### Enter “l3l” as the password.
> Note: This is lower-case L, 3, lower-case L.
