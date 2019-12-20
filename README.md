# toDoManagerBuildFE


toDo app RESTAPI : http://api.webdevk.com/api/v1/

Application Description : 
This application is a to-do manager, that can be used for daily management of todo’s a person wants to complete and can be used mostly as a reminder to do stuff they want to. It can be used to manage the list of activities a person wants to do before a due date. 
It can be used to create a list of activities with different items in each list. It also has the option to add sub-to-do items to a particular list item. 
The application allows people to add friends to see what activities they plan on doing. Adding a friend also allows the user to see the friend’s to-do’s
The application also gives the friends to change to-do lists and to-do list-items of a person.
Only a friend of the user can see the user’s to-do’s.


User Management : 

SignUp:
A new user can signup with the toDoManager by creating a new account, by providing all the required details. 
All fields are mandatory. And users should note that they should provide a mobile number they remember the most, as this is required if the user forgets password

Login: 
Users can login to the application by using email and password.
This page also provides the users with forgot password option. It is required for the user to remember the mobile number that the user used while signup for this option.

Forgot-password: 
This functionality allows the user to get to a link that can be only accessible on providing correct mobile number that the user provided during signup. This page will be only accessible for a limited time before which the user has to reset password
On entering correct mobile number the user will be taken to a new page where they can reset the password.


ToDo Manager:

List:  

Create new list : It allows users to create new list in the dashboard after login. User will not be able to create a list with the same name as one that is already open. An item has to be move to done state for being able to create a same list title again.
On clicking “create new list” the form pop’s up to allow user to create a list
The user must first click the list name to be able to do further actions on it. Like creating an item in the list. For instance, to create a new item in the list “buy groceries” the user has to click the “buy groceries” list title on the left side to access its details and perform actions on it.

Edit list : This allows user to edit the list details like list title and list description

Delete List : this allows the users to delete the list selected. It has to be noted that this deletes the entire content of the list, including all items and there is not reverting

getUserAllLists : This allows users to get all the lists that the selected user owns. This can be used to load lists on selecting a user or loading all the lists of the user on loading page

Undo : This allows users to undo the most recent action done on the list

Redo : This allows users to redo the most recent action done on the list.

List Done : Allows user to mark a list as done

Re-Open : This allows users to revert a completed list to open state from the done lists section

The done lists section only has delete and re-open list options.

Item : 

The following are all the options available on the items of a list.

createNewItem:
This allows users to create new items in each list. It also prevents users from making items with same names as it will be redundant 
On clicking create new item after selecting a list, the user will be able to create an item in that 


Options on items:
On selecting particular item the user will be given details of the item and also the sub-to-do items if any available. Following are options that are available on an item on clicking the options button of the item.

editItem : This allows users to be able to edit items details like item title, item description and due date of the item.

Create a sub-to-do item : This allows users to create a sub to-do-item in an item.

deleteItem : this deletes the selected item in a list. There is no reverting.

undoAction : it undoes the late committed action on the item

redoAction : it allows users to redo the most recent undo action on the item

markItemAsDone : Allows user to mark an item as done.

markItemAsOpen : This allows users to revert a completed item to open state from the done item section

Items that are done will only have options to delete an item or re-open the item.


Friend Manager:

sendFriendRequest : This allows users to send friend requests to users of the toDoManger app. A user can send a friend request to anyone that is a user of the app. 

CheckRequest : This allows the users to see a list of pending/new friend requests they received
Once a user gets friend request notification, they can check the pending friend requests by selecting the friends icon on the navigation bar on top of the page.


acceptFriend : This allows users to accept friends from pending/new list of requests. Adding a user as a friend gives them authorization to create, read, edit and delete items and read only for lists. 
Once the friend request is accepted, the friend’s list will be all visible and all the CRUD operations can be performed on the friends account.


toDo app RESTAPI : http://api.webdevk.com/api/v1/

