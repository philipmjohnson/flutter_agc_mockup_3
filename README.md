# Flutter mockup of the Agile Garden Club app

This repository contains the third increment of work on a mockup of the [Agile Garden Club](https://agilegardenclub.com) application. 

The main changes in this version are:

* The use of Riverpod for state management. The data model entities are now accessed using Providers.
* The ability to add and edit garden data using the Add Garden and Edit Garden pages. 

## Screen shots 

Here are screen shots that illustrate current application state. We use the flutter_markdown package to provide information on what should appear in a page when we haven't gotten around to actually mocking up the contents.   

Click on any screen shot to see it full-size.

### Splash, signin, and signup pages:

<p style="text-align: center">
  <img src="./README-screenshots/splash.png" width="30%">
&nbsp; &nbsp; 
  <img src="./signin.png" width="30%">
&nbsp; &nbsp; 
  <img src="./signup.png" width="30%">
</p>

### Home page: My News, My Gardens, My Discussions

<p style="text-align: center">
  <img src="./home-my-news.png" width="30%">
&nbsp; &nbsp; 
  <img src="./home-my-gardens.png" width="30%">
&nbsp; &nbsp; 
  <img src="./home-my-discussions.png" width="30%">
</p>

### Navigation Drawer, Gardens, and Chapters pages

<p style="text-align: center">
  <img src="./drawer.png" width="30%">
&nbsp; &nbsp; 
  <img src="./gardens.png" width="30%">
&nbsp; &nbsp; 
  <img src="./chapters.png" width="30%">
</p>

### Add Garden and Edit Garden

<p style="text-align: center">
  <img src="./add-garden.png" width="30%">
&nbsp; &nbsp; 
  <img src="./edit-garden.png" width="30%">
</p>

### Outcomes, Seeds, Members pages

<p style="text-align: center">
  <img src="./outcomes.png" width="30%">
&nbsp; &nbsp; 
  <img src="./seeds.png" width="30%">
&nbsp; &nbsp; 
  <img src="./members.png" width="30%">
</p>

### Discussions page

<p style="text-align: center">
  <img src="./discussions.png" width="30%">
</p>

### Help

<p style="text-align: center">
  <img src="./help.png" width="30%">
&nbsp; &nbsp; 
  <img src="./help-local.png" width="30%">
</p>


## Installation

This app can only be run locally in development mode. To install and run:

* Clone this repository to your computer.
* Bring up an IDE such as IntelliJ on the repository.
* Run the app within a simulator. 

## DartDoc

Unfortunately, `dart doc` does not yet provide useful documentation for this mockup, since almost all of the code resides in the `src` directory.  This should be addressed soon, see <https://github.com/dart-lang/dartdoc/issues/3096>.
