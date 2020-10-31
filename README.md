# cs262-service


**What are the (active) URLs for your data service?**

https://mighty-coast-23811.herokuapp.com

https://mighty-coast-23811.herokuapp.com/players


**Which of these endpoints implement actions that are idempotent? nullipotent?**

The PUT, DELETE, and GET methods are idempotent. 

Queries are nullipotent because they return useful data but do not change the data structure. 

**Is the service RESTful? If not, why not? If so, what key features make it RESTful?**

The service is RESTful because of the following points:

 - utilizes HTTP methods
 
 - supports JSON and HTML
 
 - shows resources via URL (e.g. /players/1)
 
 - uses stateless operations

**Is there any evidence in your implementation of an impedance mismatch?**

