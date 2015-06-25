MVC4 Forms Authentication Example
===================
Original source code from
http://primaryobjects.com/CMS/Article147.aspx

A basic example of using MVC4 forms authentication with a custom membership provider and custom principal.

Upon logging in, user data is stored in the encrypted forms auth cookie. This allows you to have global access to the user profile data, without having to retrieve it from the database upon each request.

Vijay: Modifications made by me are,
1. Added About action method in Home controller
2. Displaying About, Index and Logoff links if user is authenticated
3. Enter "john" as username and "doe" as password to login into the application

