# Level 5

![Alt text](level5.PNG?raw=true)

#
### SOLUTION
 
### Disable Javascript
### Right click on the web page to "View Page Source"

	<script language=JavaScript>
	var pass, i;
	pass=prompt("Password: ","");
	if (pass=="SAvE-as hELpS a lOt") {
	window.location.href="save_as.htm";
	i=4;
	}else {alert("Try again");
	window.location.href="abrae.htm";}
	</script>


> The if statement `if (pass=="SAvE-as hELpS a lOt")` shows what the password needs to be.

> But you need to enable Javascript to get the password box back.

### Enable Javascript

### Enter “SAvE-as hELpS a lOt" as the password.

#
Alternatively, the URL for the next level is also in the page source.

### Next level: www.hackertest.net/save_as.htm
