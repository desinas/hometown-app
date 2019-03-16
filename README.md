# Building the Home Town app  #

The Brighton Times site with two coloumns: text and images,
also the weather and sports scores. When resize the page the content is no longer fitting the browser.
So to make it responsive:
- Add a <meta> viewport to the page with initial scale.
- Adjust CSS and markup to display in a single column. Use relative widths so to stretch elements to fit any viewport.
- Touch targets are easy to hit by finger.
- Testing the site across different viewports.

### site responsiveness improvement ###

In order to make everything display in a single coloumn, 
need to make it take the full viewport. To do that, run through the CSS looking for any containers 
with fixed widths set smaller than 100%, then simply made them 100%. So an element take as much space as it can, 
which means that if you've got a container it'll take up the viewport.
As about touch targets adding some padding:1.5em to all. After all changes manual user experience testing must be done.

###more###

Find elements that don't take all the width of the viewport,
and modify CSS width: 100%.
Touch targets made easy to hit by give them ( 48x48 )px. Give a width:1.5em to them and check it out at the DevTools element show its size, so to have at least the proper pixels.

**The repo cloned from https://desinas@bitbucket.org/desinas/start-small-mobile.git at 2018/03/08**
The final improvements done: 
* At the top news, the text is larger
* The new column in the Sports table element, sports score is hidden in mobile view ports
* Added attribute ```.location{display:block;}``` at the Sports table location column to make them show back up
* When the View port is in the desktop range the text of the Sports table is shrinked to make room for the Location column
* Changed attribute ```.snippet{display:flex; flex-wrap:wrap;}``` so at small view ports, the images to be hidden, the font size now stays at a more readable size, the text truncated after three lines, added elipses (...) at the end of each article.
* Scale down images to twice the resolution of the largest thumbnail could take. Using DevTools found this resolution is (245X164)px. Higher density means that a bigger source image might be used, so an image of (490X327)px is OK.

* Quick summary
* Version
* [Learn Markdown](https://bitbucket.org/tutorials/markdowndemo)

### How do I get set up? ###

* Summary of set up
* Configuration
* Dependencies
* Database configuration
* How to run tests
* Deployment instructions

### Contribution guidelines ###

* Writing tests
* Code review
* Other guidelines

### Who do I talk to? ###

* Repo owner or admin
* Other community or team contact
