# Flutter mockup of the Agile Garden Club app (Phase 3)

This repository contains the third increment of work on a mockup of the [Agile Garden Club](https://agilegardenclub.com) application. 

The main changes in this version are:

* The use of Riverpod for state management. The data model entities are now accessed using Providers.
* The ability to add and edit garden data using the Add Garden and Edit Garden pages. 
* The ability to login as any defined user by entering their email. The password field is not checked, you can leave it blank. The signin page updates the currentUserID Riverpod provider with the email of the defined user for access by the rest of the app. If you enter an email that is not associated with a defined user, the UI will let you know and not let you proceed to the Home Page.

## Screen shots 

Here are screen shots that illustrate current application state. We use the flutter_markdown package to provide information on what should appear in a page when we haven't gotten around to actually mocking up the contents.   

Click on any screen shot to see it full-size.

### Splash, signin, and signup pages:

<p style="text-align: center">
  <img src="./README-screenshots/splash.png" width="30%">
&nbsp; &nbsp; 
  <img src="./README-screenshots/signin.png" width="30%">
&nbsp; &nbsp; 
  <img src="./README-screenshots/signup.png" width="30%">
</p>

### Home page: My News, My Gardens, My Discussions

<p style="text-align: center">
  <img src="./README-screenshots/home-my-news.png" width="30%">
&nbsp; &nbsp; 
  <img src="./README-screenshots/home-my-gardens.png" width="30%">
&nbsp; &nbsp; 
  <img src="./README-screenshots/home-my-discussions.png" width="30%">
</p>

### Navigation Drawer, Gardens, and Chapters pages

<p style="text-align: center">
  <img src="./README-screenshots/drawer.png" width="30%">
&nbsp; &nbsp; 
  <img src="./README-screenshots/gardens.png" width="30%">
&nbsp; &nbsp; 
  <img src="./README-screenshots/chapters.png" width="30%">
</p>

### Add Garden and Edit Garden

<p style="text-align: center">
  <img src="./README-screenshots/add-garden.png" width="30%">
&nbsp; &nbsp; 
  <img src="./README-screenshots/edit-garden.png" width="30%">
</p>

### Outcomes, Seeds, Members pages

<p style="text-align: center">
  <img src="./README-screenshots/outcomes.png" width="30%">
&nbsp; &nbsp; 
  <img src="./README-screenshots/seeds.png" width="30%">
&nbsp; &nbsp; 
  <img src="./README-screenshots/members.png" width="30%">
</p>

### Discussions page

<p style="text-align: center">
  <img src="./README-screenshots/discussions.png" width="30%">
</p>

### Help

<p style="text-align: center">
  <img src="./README-screenshots/help.png" width="30%">
&nbsp; &nbsp; 
  <img src="./README-screenshots/help-local.png" width="30%">
</p>


## Installation

This app can only be run locally in development mode. To install and run:

* Clone this repository to your computer.
* Bring up an IDE such as IntelliJ on the repository.
* Run the app within a simulator. 

## DartDoc

Unfortunately, `dart doc` does not yet provide useful documentation for this mockup, since almost all of the code resides in the `src` directory.  This should be addressed soon, see <https://github.com/dart-lang/dartdoc/issues/3096>.
