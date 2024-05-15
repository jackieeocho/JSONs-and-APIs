## JSON

#### What does it stand for?
JSON stands for JavaScript Object Notation. It is an open data interchange format that is both human and machine-readable.

#### What is it used for?
it is a lightweight format for storing and transporting data between different systems, it is often used for transmitting data in web applications.

#### What it written in?
JSON is a text-based data format that is language independent by uses a structure similar to commonly used languages like python or Java. So JSON is pretty much just plain text with a specific structure for encoding data.

#### What data types can it store/use?
JSON supports the following data types:

- String: A sequence of characters enclosed in double quotes.
- Number: Numeric values, which can be integers or floating-point numbers.
- Boolean: 'true' or 'false'.
- Array: An ordered list of values.
- Objects (Dictionary): An unordered set of key/value pairs.
- Null: An empty value, represented by null.

#### What is the JSON syntax for

- Name value pairs?
```
"name": "jacqueline"
```

- Objects?

Objects are collections of nam, value pairs, enclosed in curly braces '{ }'. Each name-value pair is separated by a comma.
```
{"name": "jacqueline"}
```

- How to separate data objects from one another?

Data objects are separated from one another by using commas.
```
{"name": "jacqueline", "age":"22"}
```
- JSON arrays (these are like lists in python)?

JSON arrays are ordered lists of values, enclosed in square brackets '[ ]'. Values can be of any type, including other arrays and objects, and are separated by commas.
```
{"name": ["jacqueline", "jennifer"]}
```

#### What are APIs?
APIs stand for application programming interfaces, they are a set of rules and protocols that allow different software programs to talk to each other and share data or functionality.

#### How are APIs used and why are they popular?
APIs are used to integrate new applications with existing software and systems. This increases development speed because each functionality doesn't have to be written from scratch. You can use APIs to leverage existing code. They are so popular because they have made it possible for different applications of different origins to interact with each other. 

#### Find a diagram that showcases the API data transfer process.
https://medium.com/@deep2017.arjun/why-rest-api-for-data-transfer-f66efc31a079

#### What are REST APIs? 
A REST API (also called a RESTful API or RESTful web API) is an application programming interface (API) that conforms to the design principles of the representational state transfer (REST) architectural style.RESTful APIs are commonly used in web and mobile applications to retrieve or modify resources and data on remote systems. 

#### What makes an API Restful?
- Representational
- URIs
- Statelessness
- Caching

#### What is HTTP?
Hypertext Transfer Protocol (HTTP) is the foundation of the World Wide Web, and is used to load web pages using hypertext links.

Find diagrams that showcase:
 
#### HTTP Request Structure
HTTP requests are messages sent by the client to initiate an action on the server. Their request-line contain three elements: An HTTP method, a verb (like GET , PUT or POST ) or a noun (like HEAD or OPTIONS ), that describes the action to be performed.

https://www.google.com/url?sa=i&url=https%3A%2F%2Fdeveloper.mozilla.org%2Fen-US%2Fdocs%2FWeb%2FHTTP%2FMessages&psig=AOvVaw3NT34WtTF2cnTum0yHYve_&ust=1715865934810000&source=images&cd=vfe&opi=89978449&ved=0CBQQjhxqFwoTCNDtzfrgj4YDFQAAAAAdAAAAABAE

#### HTTP Response Structure
 An HTTP response contains a status message, response HTTP headers, and the requested object or, if the requested object cannot be served, an error message.

#### What are the 5 HTTP verbs?
- delete
- get
- head
- patch
- post
- trace