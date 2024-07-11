# RESTful Web API Design with Node.js


 # Chapter 1
  ### REST - What you didn't know.

  ####  A brief history of REST

-Back in 1999, there was a lot of excitement about something called REST, which stands for Representational State Transfer. It all started when a group of experts, including a guy named Roy Fielding, shared some important guidelines for how computers should talk to each other over the internet. They wrote these guidelines in a document called RFC 2616, which focused on a way of communicating called HTTP (the same thing you see in web addresses).

Roy Fielding then took these ideas and created a set of rules to make web communication simpler and more efficient. This became known as REST. REST uses standard web methods like GET, POST, and PUT, and it relies on URLs (web addresses) to access and manage resources, like web pages or data on the internet.

REST made it easier for different computer systems to talk to each other in a straightforward, consistent way, making the web more powerful and flexible.

- To make your web application work well with REST, here are the key principles you should follow:

1. Everything is a Resource
2. Each resource is identifiable by a unique identifier (URI)
3. HTTP methods to perform actions on resources.
4. Resources can have multiple representations (JSON or XML).
5. Stateless Communication


### Principle 1 - every thing is a resource.

To understand how REST works, you need to think about data in terms of its format rather than as physical files. On the internet, every piece of data is described by a specific format known as a content type. Here are some examples of content types:


1.1 JPEG Images: These have the content type "image/jpeg".

1.2 MPEG Videos: These have the content type "video/mpeg".

1.3 HTML Documents: These are web pages with the content type "text/html"

1.4 XML Documents: These have the content type "text/xml".

1.5 Text Documents: Plain text files with the content type "text/plain"

1.6 Binary Data: General non-text data files with the content type "application/octet-stream".

Each type of data on the internet can be identified by its content type, which tells the computer how to process and display the data. For example, when a web browser receives data with the content type image/jpeg, it knows to display it as an image, while text/html tells the browser to display the content as a web page.

This concept helps ensure that different systems can understand and use the data correctly, no matter what form it takes.







### Principle 2 - Each resource is identifiable by a unique identifier (URI)

The internet has a vast array of resources, and each should be accessible through a unique address, known as a URI (Uniform Resource Identifier). Ideally, these URIs should be human-readable, making them easier to understand and work with, even though the main users are often software programs. Human-readable URIs help keep data self-explanatory and simplify further development. They also help reduce the chances of logical errors in programming.


Here are some examples of human-readable URIs:

2.1 Images: http://www.mydatastore.com/images/vacation/2014/summer

2.2 Videos: http://www.mydatastore.com/videos/vacation/2014/winter

2.3 XML Documents: http://www.mydatastore.com/data/documents/balance?format=xml

2.4 Archive Data: 
http://www.mydatastore.com/data/archives/2014

These URIs clearly indicate the type of resource they point to:

- The first URI points to an image from a summer vacation in 2014.
- The second URI points to a video from a winter vacation in 2014.
- The third URI points to a balance document in XML format.
- The fourth URI points to archived data from 2014.

  
By making URIs clear and readable, you make it easier to identify and work with different types of resources on the internet.

















  
