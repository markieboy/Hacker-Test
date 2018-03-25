# Level 20

![Alt text](level20.PNG?raw=true)

#
### SOLUTION

> There are 2 long strings of digits on the screen.

## The first is a hex number:
436f6e67726174756c6174696f6e732532312b596f752b686176652b7061737365642b746f2b6c6576656c2b31302e2b486572652532432b7468696e67732b6265636f6d652b6d7563682b6d6f72652b6469666663756c742b2533422d2532395b486f70652b796f752b6765742b7468726f7567682532312b456e6a6f792e

> Open a Hex to ASCII converter: www.rapidtables.com/convert/number/hex-to-ascii.html

> This converts the message to:
`Congratulations%21+You+have+passed+to+level+10.+Here%2C+things+become+much+more+diffcult+%3B-%29[Hope+you+get+through%21+Enjoy.`

> This does not seem to tell you much.

## The second is a Base64 number:
VldwSk5Gb3lVa2hQUjJSclRUSlJlbFJITlU5TlIwNTBWbTE0YTFJelVqSlpNakF4WWtkT2NFNVlWbUZYUmtZeVYycEtTbG95U25SUFZFNU5Xbm93T1QwOT09

> Decode this as 4 times as Base64, reveals:

	Go to www.streetkorner.net/gb now.
	
NOTE: This link directed me to install a "safe browser extension". This looks dodgy, so I shut the site down. But you MUST visit www.streetkorner.net to get a cookie in order to complete the challenge.

> In the source code below this Base64 number is

	<font color="#FFFFFF">&nbsp;^^^^^^^^^^ Change domain, add "22332" at the end, reach it and then get hold of ... ^^^^^^^^^^
	</font>
	
> This suggests the next URL is www.hackertest.net/gb22332

> This generates a fake error message. View source code:

	<H1>Not Found</H1>
	The requested URL /gb22332/login.php was not found on this server.<P>
	<P>Additionally, a 505 Not Found error was encountered while trying to use an ErrorDocument to handle the request.

> Visit www.hackertest.net/505, gives another error message. View source code:

	<H1>Not Found</H1>
	The requested URL /505 was not found on this server.<P>
	<P>Additionally, a 403 Not Found
	error was encountered while trying to use an ErrorDocument to handle the request.
	</BODY></HTML>

> Visit www.hackertest.net/505/403/, gives: 

	What is the answer to life, the universe, and everything?

> Visit www.hackertest.net/42.php. Look at the source code:

	<A HREF="http://www.hackertest.net/">Enter</A>
	<!-- Make sure you pass referrels -->

> [By referrels, I think it means it wants the cookies from www.streetkorner.net, so visit this page if not alredy done so.]

> Click on `Enter` to proceed to the end...

![Alt text](congrats.PNG?raw=true)
