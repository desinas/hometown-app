# Buildind the Home Town app  #

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