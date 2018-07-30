# advanced_bootstrap
going deeper into the bootstrap and making a professional landing page
link for website: https://django-project-dc6f8.firebaseapp.com/

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

# Main Layout
First of all we will create a basic structure like for the other section
seperate the section with hr tags and give each section its own start and end comment for ease.
Always use comments to describe a section

.my-5 		gives margin on top and bottom (y) of 1.25rem
.mt-5 		gives margin top of 1.25rem

In main layout we have different section with different width on the screen.

# Icons
We can add icons from the class .fa .fa-bicycle from mdb icons in the i tags
increasing size of icons is as simple as adding another class .fa-1x .fa-2x .fa-3x .fa-4x .fa-5x 
in i tags.
We can also add color to our icons using the color-text in the icon(i) tags only, we have added orange color using the class .orange-text

# Heading and Description
We can add .font-weight-bold class to all the headings 
.gret-text class can be added to the paragraph tags for each description

# Sections
We have three sections in our main layout
In the first section we have two rows with three columns each within
The columns in each row has namely three classes col-lg-4 is for diving the col in three parts
on the large screen. col-md-12 is for making the element cover the whole screen when medium size.
In the second and third column we have col-md-6 which will place the two cols on the medium screen,
all these sections and columns will be device responsive.

# Image Click Redirection
To enable the image clicking and redirecting to another url then we can enclose our div .mask
with anchor tags.

# Carousel
Go the carousel section of the website and copy the basic example code for carousel
We have pasted the carousel code in the first column of the gallery section
If you want to add shadow effect then add z-depth-1-half class in the .carousel-inner div tag.
The .active class must be added to one of the carousel images or the carousel won't be visible.

# Carousel-options
We can play with the many carousel options avaliable on the docs for carousel
We can even increase the speed of our carousel using some simple jQuery by the interval value,
to stop the autoplay we can set the interval value to false.

# Contact Form
Just like the other sections we have to create a basic structure for the section first then
we will add form tags and the labels and input fields.
We have made two cols in the contact form section inside a row in which we have set the
width for the first col to be col-lg-5 which means to complete the 12 we have to set the other
col width of 7 and we have full width for medium screen as col-md-12.