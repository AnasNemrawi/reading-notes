# API Integration
## API Server Build

1. Explain the difference between query string and path parameters.

- Query String Parameters: Extra info in the URL after a ?. Used for filtering or adding data, like ?param1=value1.

- Path Parameters: Part of the URL path, used to specify a resource, like /v3/stuff/things.

2. What would our API URL with a path ID parameter be given the following information:
 ( Domain: http://our-site.com, v3, model name: stuff, id: things )
http://our-site.com/v3/stuff/things 

3. We have created a dynamic API with an “interface”. Describe how that interface works to a non-technical friend.

> A dynamic API with an "interface" is like a customizable robot. You can tell the robot what you want it to do by selecting options from a menu. The menu is the interface, and it lists all the tasks the robot can perform. When you pick a task from the menu, the robot knows exactly what to do and does it for you. It's like giving commands to the robot in a way that's easy for both you and the robot to understand.

## Auth Server Build

1. Describe how you would use middleware to implement basic and bearer auth.

- Basic Auth Middleware checks your username and password when you log in. Bearer Auth Middleware checks your special token to let you access certain areas.

2. Describe the handshake necessary to implement OAuth.

- OAuth is like giving someone a limited-use key (access token) to access (resources) without giving them a master key (password).

