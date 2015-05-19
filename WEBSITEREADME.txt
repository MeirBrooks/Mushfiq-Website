**********************README FOR MUSHFIQ'S WEBSITE************************
**************************************************************************

Last update: 5/19/2015 by Derek Wolfson


** 0 - INDEX*******************************
1 - Introduction
1.0 - Foreword
1.1 - Global Settings for the Site
1.2 - Recommended Software

2 - Individual Pages
2.1 - Index
2.2 - CV
2.3 - Research
2.4 - Media
2.5 - Ongoing Projects
2.6 - Teaching
2.7 - Affiliations
2.8 - Yale SOM Profile 
2.9 - Contact
*******************************************





*************1 - INTRODUCTION************

*********************************
*	1.0 - Foreword		*
*********************************

Mushfiq's new website was built in January 2014, using a software called BlueGriffon.  It was designed to look professional and scholarly.  Essentially it is composed of three parts:
1 - the Header, where you will find the Yale SOM Logo and Title Bar
2 - The navigation bar, where you find the links to the various pages
3 - The body

This is the basic setup for this webpage and it makes for a nice browsing experience on computers, tablets and smartphones.  



*********************************
*   1.1 - Recommended Software	*
*********************************

The global settings are as follows:

Global Font: Georgia
Global Font Size: 10pt 
Body Text Color: Black
Alignment: Justify 
Section Header Text Color: Midnight Blue [HEX:#023165, RGB(2,49,101)]
Yale SOM Header Image: found at "../resource/images/banner.png"



*********************************
*   1.2 - Global Settings	*
*********************************

BlueGriffon was the software used to created this webpage.  It is a nice What-You-See-Is-What-You-Get HTML editor that takes advantage of HTML5 and CSS3.  If that means nothing to you, that is fine, however it is important to note some of the styles are specific to CSS3.  For example, the dropshadow found on every page is part of CSS3.  

I recommend to continue using BlueGriffon to keep this webpage up to date.  Dreamweaver would be a suitable alternative, however it costs some serious money.

NOTE: using Bluegriffon creates these strange .bak files.  I'm not certain what they do but you can delete them.  If you do not delete them they cause no harm.  It is a bit of a pain, but oh well, that is what you get sometimes with freeware. 

*********************************
*   1.3 - Page Header		*
*********************************
The page header is contained in resources/common/header.txt.  This file contains a javascript document.write() command, which is subsequently used in every page to insert the header HTML at the top of the page body.  

The code: 
  <script language="javascript" type="text/javascript" 
  src="http://faculty.som.yale.edu/mushfiqmobarak/resources/common/header.txt"></script> 
is what includes this header on the webpages.
 
To change the header globally, simply change header.txt.
 
NOTE: header.txt cannot contain any line breaks, that is why it looks ugly.


*************2 - INDIVIDUAL PAGES************


*********************************
*   2.1 - Index			*
*********************************

This page is the landing page for Mushfiq's website.  It contains a brief Bio, selected achievements and awards, selected articles and his education background.

Images: 
Mushfiq's Picture: "../resources/images/mobarak_mushfiq.jpg"



*********************************
*   2.2 - CV			*
*********************************

This is just a hyperlink to Mushfiq's CV.  It routes to:   http://faculty.som.yale.edu/mushfiqmobarak/CVmobarak.pdf

If you are going to update Mushfiq's CV, replace the file "CVmobarak.pdf" with the latest copy.  Put the old copy in the Archive folder.  



*********************************
*   2.3 - Research		*
*********************************

This is the page for Mushfiq's research.  To add a new paper or article to this page just open the research.html page in BlueGriffon and add a new item to the list by doing a carriage return at the end of the list.  Just like you would in MSWord. 

NOTE: Be sure to italize the Journal Names on this page.  



*********************************
*   2.4 - Media			*
*********************************

This page contains all the media links for Mushfiq.  Add a new item just like you would in MSWord. 

NOTE: Currently the Media articles are in order with the most recent media first.  Do your best to keep these in chronological order.

	

*********************************
*   2.5 - Ongoing Projects	*
*********************************

This page contains information about Mushfiq's Ongoing Projects.  At the time of writing this readme this page needs to be updated.

Each project gets it own HTML file.  You can find the individual HTML files in "../ongoingprojects/country/project.html".

For example, India Rainfall is found at: "../ongoingprojects/india/rainfall.html"

The files for each ongoing project page are found at:"../ongoingprojects/country/files/projectnames/"

For example, the files for India Rainfall are found at:
"../ongoingprojects/india/files/rainfall/"

Keeping new projects in these sorts of branches to ensure that the webpage folders do not get messy.  Once they begin to get out of hand they are very difficult to tidy up.

When adding a new project there is a template.html file found at 
"../ongoingprojects/template.html"

This contains a working example of a project page.  Just plug in the necessary information and be sure to change the page title by opening your new project page in bluegriffon and navigating to:

Format >  Page Properties..
and Changing Title from "Template | Ahmed Mushfiq Mobarak" to "Project Name | Ahmed Mushfiq Mobarak" 

(Obviously, replace Project Name with the project's name.)



*********************************
*  	 2.6 - Courses		*
*********************************

This page contains information about Mushfiq's courses. 

His SOM courses are at the top and they contain links to Syllabi.  The convention is to have links to the three most recent Syllabi.  

You can find the Syllabi here: 
"../courses/syllabi/year/"

For example the Syllabus for MRKT522 Spring 2014 is found at: 

"../courses/syllabi/2014/Mobarak_522_2014Spring.pdf" 

Again, please maintain this structure to keep the website in an orderly fashion. 


The second part of Mushfiq's Teaching Website are individual pages for each of his International Experience Trips: 

You'll find the individual pages at: 
"../courses/intlexp/trip.html"

For example, the webpage for the 2011 trip to Brazil is found at: 
"../courses/intlexp/2011brazil.html"

Each of these pages contains a number of files necessary for the page such as pictures and itineraries.  These are found at: 
"../courses/intlexp/resources/year/"

For example, the files for the 2011 trip to Brazil are found at: 
"../courses/intlexp/resources/2011/"


Again, please maintain this structure for tidiness (sp?).

To add a new international experience page use the template found at: 
"../courses/intlexp/template.html"

Just plug in your information and create a new folder for the files necessary for that page in "../courses/intlexp/resources/XXXX" where XXXX is the four digit year.  Be sure to change the page title by opening your new project page in bluegriffon and navigating to:

Format >  Page Properties..
and Changing Title from "Template | Ahmed Mushfiq Mobarak" to "Country Year IE | Ahmed Mushfiq Mobarak" 

(Obviously, replace -Country- and -Year- with the necessary information for the new page.)




*********************************
*  	 2.7 - Affiliations	*
*********************************

This is the page for Mushfiq's affiliations.  

At the top are `appointments' which have a bit of a explanation after them.  
If you want to add another appoinment to the list follow these steps:

1 - Copy the text from one of the existing appointments 
2 - Carriage return at the end of the last appointment
3 - Paste the copy text
4 - Add whitespace where necessary
5 - Insert the information for the new appointment in the proper area. 

The reason you should do it this way is that in this itemized list it is difficult to get the text to look the way it looks in the appointments without editing the HTML source code.  Essentially there are <br> tags on various items so that it does not create a new item and only a new line.  It isn't that confusing, but it gets clunky in bluegriffon.

If you absolutely must add another line (but not another bullet) then follow these steps: 

1 - Highlight the text before where you want another line.
2 - at the bottom of the BlueGriffon window change from -Wysiwyg- to -Source-
3 - Enter the code <br> to enter a line break.
4 - Go back to -Wysiwyg- and you should have another line without the bullet to type on. 


Below appointments is "Other appointments" 

To add another -other appointment- follow these steps:

1 - Copy the text of the last `other appointment' 
2 - Triple Carriage return to get to a new line (the first carraige will give a new line, the second carriage a bullet, and the third carriage will clear the bullet)
3 - Paste the text you have copied
4 - Replace the text with the new text for the new appointment
5 - Don't forget to change the link. 


I'll admit -- this page is a bit of a mess, but it is the only way it woudl work.  This is the downfall of WYSIWYG programs like BlueGriffon, but their BlueGriffons MB > BlueGriffons MC. 



*********************************
*     2.8 - Yale SOM Profile	*
*********************************

This is the link back to Mushfiq's Yale SOM Profile.

At the time of writing the address is: 

"http://som.yale.edu/ahmed-mushfiq-mobarak"

If this ever changes, we'll need to update this link on EVERY page.

Every Page is these three categories:

1 - All .html files found in the main directory (e.g. Index.html, contact.html, etc.)

2 - All international experience .html files.  Found in "../courses/intlexp/*.html"

3 - All ongoing project .html files.  Found in:
"../ongoingprojects/country/*.html"

Let's just hope they do not change this link!! 


*********************************
*  	 2.9 - Contact		*
********************************* 

This page contains Mushfiq's contact information.  I imagine he'll be in Evans Hall for awhile, so I don't think this should change too frequently.  

However, his Administrative Assistant may change.

Try to keep this updated.









