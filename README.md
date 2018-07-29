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

# Image
The images we upload from our server or any other url source should be small files or else images
will increase the page load time
Images should be small enough to maintain quality and as lightweight as possible.

Image Requirements for a website:
RESOLUTION: 1920px/1280px
FORMAT: jpg format
COMPRESSED FILE: http://compressjpeg.com/

# Overlay Content
.display-4 		creates a huge heading
.font-weight-bold 		makes heading heavier
.white-text 	makes heading white
.hr-light 		makes divider light

.btn-outline-white		creates a transparent button
.fa-book		one of 700 mdb icons

Centering the content can be done with flexbox
.d-flex 		gives the element flex property
.align-items-center		center aligns the flex items

# Improve overlay
.container-fluid	for using row and cols we need to use a container for parent
.justify-content-center		aligns content horizontally
.row 		for grid construction inside containers
.col-md-10		content won't be stretched on wide screens and render nicely on small screens too
.text-center 		center our content within the column
COMPRESSED FILE: http://compressjpeg.com/

# Content on intro
For adding content on the intro image we need to keep some contrast between our image and the 
content on top of it so for that we can add another class
.rgba-black-strong		adds strong black contrast
.rgba-black-strong		adds light darkness