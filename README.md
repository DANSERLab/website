## MT Lab Website
### Overview
This website was made for use by the MT Lab at UCSC by Noah Brown Erik Jung and Gordon Keller.
Made to be a simple non Drupal based lab website that will be able to continuously maintained
and edited by anyone with funcitoning html and css knowledge. Javascript is minimally used 
for a bit of added functionality (e.g. nav opening closing) but other than that it is pure
HTML/CSS
### Adding Pages
As time continues undoubetdly there will be new pages to add. In the templates folder are two
html files to assist in the creation of new pages. "simple.html" is a basic webpage layout with
placeholder lorem ipsum text. This is the design used by all our project pages so for consistency
it should continue to be used for end pages (where the user has navigated to the end of their 
journey). Additionally there is an "example.html" which, as might be expected provides examples. 
It serves as essentially a lookup table of how most html elements will appear under our given
css. It can be used if the dev knows what element that want and wants to see how it will look
before implementation, or vice versa if the dev wants to search through and find what look
suits their needs. 

### Pitfalls
By far the most common pitfall will likely be incorrect pathing to link everything together. 
Since pages are not dynamically generated all files will be linked relative to the current
page. For the most part it won't be a problem but just requires a concientious effort
when creating a page at a new folder depth from the root. Very easily spotted if the page
is QAed before going live. 

### Bugs
Bugs are inevitable, if you see a bug or a typo there are two possible actions:
1. handle it yourself (preferred)
2. email me at n.ebrown47@gmail.com with a description of the bug and I will take care of it

In the case of something that is less of a bug and more of a missing feature/foundtional part
of the website, shoot me an email at the above and, if you are comfortable with git, add it
to the TODO list below. 

###### TODO
	* Change titles to have info about specific page
	* hook up buttons on front page
	* update with new forms info
	* Remove all traces of stock imaging
	* Change tagline of DANSER acronym
	* Use or remove linkedin facebook etc icons at footer
	* ~~add all publications~~
	* ~~Align MS Students in members~~
	* Create/link videos page
	* Ceate/link Research landing page
	* Make sure all research content is good/up to date
	* Add favicon.ico