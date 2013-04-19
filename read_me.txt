The book is wrapped in a div container called "myBook" in the html file bookflip.html, there is no need to enter bookflip.js unless you are a advanced with javascript.
eg:
<div id="myBook" style="display:none;">	

	

Within this div go your pages, they should be properly closed html elements, in the example and for best results they should be <div></div> elements.
eg:

<div name="Home" style="background:#055123 url(spongebob300/page0.jpg);color:#ffffff;">
			<div align=center>
			<h1>Are You Ready Kids?</h1>
			</div>
		</div>

The above div is found by the bookflip.js script and uses it as page nought (0 is base number in javascript not 1).
By giving the div a name attribute (name="Home") the script can add the name instead of page number to the dropdown page list.

Below that can go any number of divs(pages), the only limitation is how well the viewers browser and browser's javascript engine can cope with what you have inserted.

Each page div is sized according to the settings at the bottom of the html file containing the book:
var myPageW=300; //page width
var myPageH=361; //page height

Other setting are named to be as self-explanatory as possible.


It is best to have some basic knowledge of html or have someone assist if you are still learning. But as a guide it is best to use the demo as a template and modiy/add your content and or pages as required.
To see how a page might look as a stand alone, paste the div(page) code to a seperate html file, give the div the same height and width attributes as your myPageW and myPageH settings and load into a browser.

eg. div with height width settings as new html file:

<div name="Home" style="width:300px;height:361px;background:#055123 url(spongebob300/page0.jpg);color:#ffffff;">
			<div align=center>
			<h1>Are You Ready Kids?</h1>
			</div>
		</div>

Please review the comments section of the website (http://coastworx.com/bookflip.php) as there is a good chance any questions you may have, have already been asked and answered and its a couple of pages long. 
If you need help with basic html ask a friend who can help or hire a professional.

Cheers
Will



