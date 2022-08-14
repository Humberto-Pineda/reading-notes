# Class 13

> Why would a developer use local storage for a web application?

In order to avoid have a user set up a username, password, or any type of account. HTTP is **stateless** and if you close a wesite and open it again, it will revert to its original state and not save any pertinent information for the user

> What information should not be stored in local storage?

getJson should not be stored locally

> Local storage can store what type of data? How would you convert it to that type before storing?

It can only store *strings*  so you can change that using json.parse and json.stringify