# CodeSummaryAzureDevOpsProject-AppBuilder9000
This is the code summary for Appbuilder 9000.  The Tech Academy live project utilizing Azure DevOps and Git

 ##Code Summary for Azure DevOps Web Application Development Team Project -

###AppBuilder9000 - A web application that houses several individual apps to track and store collectable items.

####This project was composed of and used the following technologies.

- 2 week live project sprint
- 10+ Python Developer Team Members 
- 10 daily standups Discord meetings
- 2 weekly code retrospects Discord meetings
- Django Framework
- Languanges used: HTML, CSS, JavaScript, Python
- Template pages: HTML, Django, JavaScript, CSS, Bootstrap
- View Functions: Python


####User Story #1

**Description-**
*Create a new app for the project, named appropriately for what you are tracking, 
and get it to display a home page with basic content.* 

- This story was the introduction.  I cloned the project to my machine using git 
  for source control and PyCharm for the IDE utilizing the Django Framework.  
- After virtual environment created, dependencies downloaded and branches created and updated, 
- I added my name to the group sign in template page along with my collectable item and app name. 
- I created my app titled Workout Equipment to track and store home and commercial gym owners equipment. 
- I created a CSS asset and HTML template page that displayed the image to the main project home page where all other team
  members apps were located.
- Commited and created pull request for merge, pull then merged with master.


####User Story #2-3

**Description-**
*Create a model for the collection item you will be tracking and add the ability to create a new item.*
  
- built all template pages 
- added to entire project urls.py file installed apps
- mapped url patterns ,created blank -background img
- home & base templates created.
- base template styling for pages including background image displayed for all pages 
 
- Created database Schema with all fields and migrated changes.    
- built database structure model 
- created form with csrf token to display form table info
- built console template added create item to views for beginning of CRUD functionality
  utilizing primary key to display details of individual item on form
- Commited and created pull request for merge, pull then merged with master.


####User Story #4

**Description-**
*Create a details page that will show the details of any single item from within the database, as selected by the user. 
Link this to the index page for each item.*


- Added Your Collection tab to navbar that links to form displaying results of all database objects
- Created table template details to display all previously user added
  items to database within a table 
- Added view function to display content on template 
- mapped associated url pattern
- Utilzing bootstrap and own css combonation styling and updated background 
  images for better UI
- All template styling inherited from base document
- Commited and created pull request for merge, pull then merged with master.


####User Story #5

**Description-**
*Allow for edits and delete functions to be done from the details page or from separate pages. Have confirmation before deleting.*


- Added details page for individual profile ui template
- Added another edit page template linked through profile details page 
- Added delete template page for individual item deletion. 
- Mapped all associated url patterns and created view functions 
  that are triggered by user action (clicking button)
- Utilzing bootstrap and own css combonation added cleaner 
  styling to all pages 
- Commited and created pull request for merge, pull then merged with master.

####User Story #6

**Description-**
*Create a new template for displaying information sourced from another website. Use Beautiful Soup to data scrape the site and find the relevant information.*

Added template file, mapped url pattern, created new 
view function to scrape webpage, added navbar link to equipment info to webscrape output

- Added notes and cleaned up spacing and code
- created delete confirmation page to ensure user wants to delete
  selected item before deleted, addtional window pops up "are you sure?"
- Using beautiful soup module in view function for web scraped blog title and article information
  not for display yet just print to terminal to test parsing before display in next story pt2.
- Commited and created pull request for merge, pull then merged with master.


####User Story #7

**Description-**
*Parse through the html returned and display the information you want to display. Make sure you are getting into the individual elements
and stripping away any formatting you don't want. Add a link from your app's home page.*

Added to view function to display data on template page,  Added links to source and styling

- Added to view function to display information to template page
- Added styling to block tags that take the webscraped content
  for better asthetic
- Completed 2nd step of beautiful soup web scrape
- Commited and created pull request for merge, pull then merged with master.


####User Story #8

**Description-**
*Connect to your chosen API and get the JSON response, add in a template for displaying the information.*

Added link to nav, created template page, created view function for json API response in terminal. 
Will isolate specific data on pt2

- API found for useful exercise database info with gif for display
- Connected to API through python view function for terminal print display
- created base linked template page for API page for display.
- mapped url patterns
-created link through navbar for click activated template page display


####User Story #9

**Description-**
*Go through your various templates and add improvements to the UI/UX. 
This may include hover effects, pop-ups, animations, changes to the existing styling, etc. 
Show off your creativity and styling ability.*

Added JavaScript slideshow with imgs to console page displaying different gym setups, 
added CSS animations and styling to navbar and other text

- Updated models for more database choices for user equipment additons
- Added Javascript file for a slideshow display for different gym setups
- Added slideshow to console page where user is prompted to add equipment
- Incorporated CSS with html and javascript to acheive coheisive display
  that can be controlled via cursor arrows or navigation dots below slideshow 
  each navigation are JavaScript functions
- Cleaned up code added notes and removed excess content
