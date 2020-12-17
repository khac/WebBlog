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
### Flask SQLAlchemy
### Database Relationships

## User Logins
### Password Hashing
### Logging users out

## User Registration

## Profile Page
### Avatars

## User Followers
### Adding Followers
### Obtaining Posts from Followed Users
### Adding comments

## Submission of Blog Post

## Displaying Blog Posts

## Password reset Tokens
