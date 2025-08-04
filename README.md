# Contact Manager App

 ## This is a Crud App that utilizes AJAX, the Fetch API, Class Object creation style, and Handlebars to be able to make a contact list with some useful functionality. Please do the following to be able to use and run this app properly. 

1. Download the file and then in your editor or CLI run `npm install` to download all dependencies. node version 18 or higher should be safe to use. 

2. use the command `node contacts.js` to set start the application on local host 3000. 


## How to use this app

### Adding a contact 

1. Select Add contact to open up the contact form 

2. For the Full name section make sure to put a first and last name of atleast 1 or more alpha digits with a single space in between


3. An email must include alphanumeric values followed by @ and some email that finishes with .com

4. A number must follow in this format (xxx-xxx-xxxx) all values being numeric. 

5. Hit cancel to go back to main page. 

### Using tags

1. In the add contact form you can also add tags. To add a tag simply input some info and hit `Add Tag`. In this form you can delete the same tag by clicking on `Click to delete (tag name)`

2. Back in the home page. You can click on the middle `All Tags` section and swap to all available tags. Selecting a tag will filter all contacts by those that have the given tags. 


### Using the Search feature 

1. This feature uses the names of the contacts to filter contacts. entering any valid name will filter out all contacts that do not much. This feature is based off of the characters that are within each name. It does not have to be entered in order of the name. So for example if a contact is named `Sam Johnson` typing `ohn` will still find this contact. 


### Editing Contact 

1. In the main page you can click within any contact to edit the current content. This will pull a similar form to when you add a new contact. All of the same rules apply. Just make sure to hit `Save` to record the changes. 



### Deleting Contacts 

1. Click on the delete button within any contact to remove that contact from the list. 



## Miscellaneous 

If You have any thoughts or feedback, please let me know. :)
