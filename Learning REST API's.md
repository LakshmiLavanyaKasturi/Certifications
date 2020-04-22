# REST API: 

Representational State Transfer refers to a group of software architecture design constraints that bring about efficient, reliable, and scalable systems. 

#### REST Methods
* Get
* Post
* Put 
* Patch
* Delete
* Options
* Head

_**Get**_ requests may contain the following 
* Host
* Content Type
* Authorization
* Cache Control

Example of _GET_ request in JSON format 
![](C:\Users\lavan\Pictures\Screenshots)

_**Response**_ usually contains 
* Required : True/false
* Description
* Type 

_**DELETE**_ request,
_If force=true is given in the URL, then post will be completely deleted. 
If just delete request is passed, then it will be sitting in the trash bin.
Content type should match in GET and POST request
Same URI for GET and POST

* POST: Create new resource.

![Example of _Post_ request](C:\Users\lavan\Pictures\Screenshots)

* PUT: Contains ID and content._(Updating an existing resource and may allow it to create a new resource.)_

![Example of _Put_ request](C:\Users\lavan\Pictures\Screenshots)

* PATCH: Modify the existing resource using ID. 

![Example of _Modify_ request](C:\Users\lavan\Pictures\Screenshots)

* DELETE: Deleting data based on  ID

![Example of _Delete_ request](C:\Users\lavan\Pictures\Screenshots)

* OPTIONS: Creates description of the resource. 

* HEAD: retrieves the head section of the response. 

STATUS CODES: 

* 1XX - Information
* 2XX - Success 
* 3XX - Redirection
* 4XX - Client Error
* 5XX - Server Error

 
 
