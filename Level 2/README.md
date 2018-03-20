# Level 2

image

#
### SOLUTION
 
### Right click on the web page to "View Page Source"

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

> The if statement `if (pass=="l3l)` it adds this to the href in the link to the next level 'href="http://www.hackertest.net/"+pass+".htm"'

### Enter “l3l” as the password.
Note: This is a lower case L, not the number 1.
