# Level 1
 
> 1. View the Page Source:

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

>Notice the check for “if (document.a.c.value ==a) {….}
>Two lines above this var a is set to “null”
>2. Enter “null” as the password
