# GirmitiImageSearchApplication
# imageSearchApplication
Image Search App

Version - 1.0.0
Submitted date - 26-04-2021
Prepared By - Ravi Teja V
Reviewed By - Jom George

#Introduction : 	
This document describes the use cases for user to open web application.
# Requirement :
Coding Challenge :: Images Search App
Implement an Interface that allows users to to search for images using any FREE images search API such as:
	Unsplash
	Flickr
The results should be updated live as the user type into the search box:
Each image display some information when hover:
	Link to author page
	A button to save the image to the user’s favorite page.
	When click, show a pop up for the user to choose which list to add the image to.
	If there’s no list, allow the user to create a new list
On the Favorite page:
	Display all lists with correct images in each list
	Edit list title & description
	Click on each image should trigger the download.
Rquirements
Use any version of Angular
Use `ngrx/store` for state management
Use `ngrx/effect` for handling side effects
Use any CSS preprocessor of your choice
The project should include a README file

Use Cases
#Search Photo - Module 
1.User opens website 
2.By Default, the home screen is displayed
3.This use case shall enable the user search of the image by keying in the desired keyword.
4.By Default, the home screen is displayed
5.The home screen shall have the following options
   ->Search Photos
   ->Your personal Menu for favorite navigation
   ->Home
   ->Pagination
   ->On hover the photo 
	 -Option to add favorite
	 - Link to author page
       -Option To Download
6.User enters the text into the search box.
7.User shall either “Enter” after typing the desired keyword or shall choose from the displayed Keyword list
8. Based on the keyed in text, search result shall be displayed on the page
9. Once the search results are displayed, user can hover over the image which shall have the following options and details
   -> Add to Collection (button)
   -> Author information (view only)
10. If no results are available for the searched keyword, the page shall display “No photos Found” message
11. The search result displayed on the screen shall be based on the unsplash api

#Collections - Module 
#Add to Collections

1. This use case shall provide the access to the user to search the image and add the image as user’s favorite.
2.Once the user enters the text into the search box, the application shall have the following option to choose:
	->Search box shall display the suggestion for the user selection.
	->User clicks the ‘Enter’ button or can click on Search icon.
	->Application shall display the list of images of the searched text with the name of the searched text
	->Each image shall have the following option to view and choose when user mouse hover on the image:
	->Option to add the image as user’s favorite. 
	->Name of the author (Clicking on author name triggers navigate to author profile page)
	->Navigation link fro author
3.In an image, when user click “’+’ option (Add as favorite)” option, and application shall display a popup with the below options to view and choose:
	->Selected Image <In the left side of the popup>
	->Add to Collection <Non-editable heading>
			- Create a new collection <option>
	->List of already created/added collections name with ‘+’ option in the right to add the selected image in the collection.
4.On clicking the option - 'Create a new collection', application shall display an option – 'create a new collection' with below options in order to create new collection:
	-Name
	-Description (optional) 
-	-Create collection <Button>
	-Cancel <Button>
	-User fill the fields of ‘Create a new collection’.
	- Click the ‘Create collection’ button
5. User select the collection or click ‘+’ option from the list

#Edit and Delete Collections
1. opens the application User clicks the 'faviourite’ link from the top right corner of the page by clicking on author.
2.Once the user clicks the option – ‘Your personal menu button’, the application shall have the following option to choose: Favorites
3.User clicks the ‘Favorites’ option from the above given option.
4. On clicking the ‘Favorite’, the application shall navigate to the next page with the below options to view and choose: 
Collections <Tab>
5. User select a collection from the list.
6. On selecting the collection, application shall open all the images which was added in to that collection.
7. Each image shall have the following option to view and choose when user mouse hover on the image:
	->Name of the author <Bottom left corner of each image>(Author Name should be clickable)
	->Round Pic/Image of the author <Bottom left corner of each image>
Download Photo <option>

#  Favorites - Module
1. This use case shall enable the user segregate items and stores items in date wise folder
2. Initially, user opens the application
3. User enters the text into the search box.
4. Images are already stored/saved into the database in order to display it from the application.
5.Backend application stores item in DB in date wise format
6.User selects option from the web application for arranging items in “Date wise or Date folder wise”
7.Application shall list out all the items in Date wise condition



