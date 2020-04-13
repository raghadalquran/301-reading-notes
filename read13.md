# SUMMARY #

- At it's most basic, the web uses a client/server architecture that can be summarized as follows. 
- a client (usually a web browser) sends a request to a server (most of the time a web server like Apache, Nginx, IIS, Tomcat, etc.), using the HTTP protocol. 
- The server answers the request using the same protocol.
- An HTML form on a web page is nothing more than a convenient user-friendly way to configure an HTTP request to send data to a server.
- This enables the user to provide information to be delivered in the HTTP request.
- The <form> element defines how the data will be sent. All of its attributes are designed to let you configure the request to be sent when a user hits a submit button. 
- The two most important attributes are action and method.
- The action attribute defines where the data gets sent. Its value must be a valid relative or absolute URL. If this attribute isn't provided, the data will be sent to the URL of the page containing the form — the current page.
- The method attribute defines how data is sent. The HTTP protocol provides several ways to perform a request; HTML form data can be transmitted via a number of different methods, the most common being the GET method and the POST method
1. The GET method.
1. The POST method.

### Security issues ###
- Each time you send data to a server, you need to consider security. HTML forms are by far the most common server attack vectors (places where attacks can occur). 
- The problems never come from the HTML forms themselves — they come from how the server handles data.

![Image](https://apachebooster.com/blog/wp-content/uploads/2017/06/http-request1.jpg)

