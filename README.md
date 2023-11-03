# Chat Application

- server-side rendering  chat application  built on [NodeJs](https://nodejs.org) and [Socket.io](https://socket.io)

## Key Features

* Authentication and Authorization: 
  * Signup , Login and Logout 

* real-time notifications:
  * addFriend : 
  this requset send a friend request to specific user  when ever i click the addFriend button the user will be notified 
  i make this feture with socket.io  

* Friends request Operations : 
  * Accept: 
  assume you received a friend request from any user :
   -  1) add  this user to my frinds list  and delete him from my friendRequests
   -  2) add myData to this user frinds list and delete myData from his sentRequests
   
  * Reject : 
   -  1) delete user data from my friendRequests
   -  2) delete myData from user sentRequests 

   assume i sent a friend request to user 
  * Cancel :  
   -  1) delete user data from my sentRequests
   -  2) delete myData from user friendRequests 



## Technologies Used

* [NodeJS](https://nodejs.org/en/) - JS runtime environment
* [Express](http://expressjs.com/) - The web framework used
* [Mongoose](https://mongoosejs.com/) - Object Data Modelling (ODM) library
* [MongoDB Atlas](https://www.mongodb.com/cloud/atlas) - Cloud database service
* [Bootstrap](https://getbootstrap.com/) - Bootstrap

## Getting Started

Provide instructions on how to get a copy of your project up and running on a local machine.

### Prerequisites

What things the user needs to install the software and how to install them.

