# WebBlog
All Flask applications must create an application instance. The web server passes all
requests it receives from clients to this object for handling, using a protocol called
Web Server Gateway Interface.

Clients such as web browsers send requests to the web server, which in turn sends
them to the Flask application instance. The return value of this view function is the response
the client receives. If the client is a web browser, this response is the document that is
displayed to the user in the browser window.

A request object, which encapsulates the HTTP request sent by the client. There are two contexts in Flask: the application context and the request context.

## User Login Form
Rendering HTML forms and submitting forms through POST request. Responding to POST requests with a redirect instead of a normal
response, Post/Redirect/Get pattern.

### Generating Links

## Database
### SQLAlchemy
SQLAlchemy is a powerful relational database framework that supports several database backends. 
It offers a high-level ORM and low-level access to the database’s native SQL functionality.
### Database Relationships
Roles and Users

## Emails
### Email Support

## User Logins
With Flask-auth and decorators

## Account Management
### Password updates
### Password resets
### Email address changes

## User roles
### Role Assignment
### Role Verification

## Profile Page
### Avatars
### Profile Editor

## Blog Posts
### Paginating Long Blog Post Lists
### Editor 
### Permanenet Links

## User Followers
### Many to Many relationships
### Adding Followers
### Obtaining Posts from Followed Users
### Adding comments
