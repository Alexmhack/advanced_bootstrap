# advanced_bootstrap
going deeper into the bootstrap and making a professional landing page

# Preparations
First of all we are going to unzip our kit into the git repo
Then we are going to open index.html, the only file which we are going to modify.

# Basic Structure
Open index.html and write the basic structure for our project along with ending and starting 
comments for each section we are going to have on the page.

# Navbar
.fixed-top		for fixed top navbar
.container 		enclose all inner elements of navbar with a container div for centering navbar

# Full page Intro
.view 			wrapper for background image, enables adding a mask
Note: With mask we can make our image darker or lighter
.mask			element with absolute position, covers our background image

We will add some CSS of our own to handle our intro id element, add CSS in style.css which is 
empty for our CSS code.

# CSS
height: 100% 		We set the parent elements of the whole html file to full height because
					only that way we can cover the entire screent with our image
intro 				we can set our intro id to a proper image url
background-size: cover 		image covers all the available space on screen
-webkit -moz -o makes sure our code works properly on every browser
