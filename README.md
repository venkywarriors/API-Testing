# API-Testing

![alt text](https://miro.medium.com/max/723/1*OICaHvjcxhpFofj6Bai6aA.jpeg)

RestSharp is a comprehensive, open-source HTTP client library that works with all kinds of DotNet technologies.  It can be used to build robust applications by making it easy to interface with public APIs and quickly access data without the complexity of dealing with raw HTTP requests.

[RestSharp Basics](https://github.com/venkywarriors/API-Testing/blob/master/RestSharp-3.pdf) <br>
[RestSharp Vs RestAssured](https://github.com/venkywarriors/Restshap-with-c-sharp/blob/master/RestSharp%20Vs%20RestAssured.pdf)<br>
[Rest Vs SOAP](https://github.com/venkywarriors/Restshap-with-c-sharp/blob/master/soap%20and%20rest_removed.pdf)<br>
<a href="https://www.tutorialspoint.com/http/http_status_codes.htm">HTTP - Status Codes</a><br>

### How to write JSONPath expressions
JSONPath is a query language for JSON, similar to XPath for XML. AlertSite API endpoint monitors let you use JSONPath in assertions to specify the JSON fields that need to be verified.<br>
<a href="https://support.smartbear.com/alertsite/docs/monitors/api/endpoint/jsonpath.html">JSONPath notation</a><br>
<a href="https://docs.hevodata.com/pipelines/miscellaneous/how-to-write-jsonpath-expressions/">JSONPath Syntax</a><br>

### How to Use Base 64 Encoding in Header 
The auth code and client credentials grants require the auth code to be passed in the Authorization header using base 64 encoding. Many HTTP/REST libraries will handle the formatting and encoding for basic authentication requests, though not all do. This page serves to provide an explanation of the encoding process.
#### The Authorization Header
The Authorization header is the format Authorization: Basic encodedString, where encodedString is the result of base 64 encoding the OAuth client's values as clientId:clientSecret.<br>
<a href="https://docs.smsportal.com/docs/rest-examples">Base 64 Encoding</a><br>

### How to make a Post SOAP request with XML fields in RestSharp?
<a href="https://developer.channeladvisor.com/authorization/soap-api-credentials-flow/rest-request-access-endpoint">Post SOAP request</a><br>
<a href="https://stackoverflow.com/questions/59908572/how-to-make-a-post-soap-request-with-xml-fields-in-restsharp">Submit SOAP request via Rest api</a><br>

## Selenium exceptions
<a href="https://www.katalon.com/resources-center/blog/selenium-exceptions/">Common exceptions</a><br>

## Synchronous vs. asynchronous communications
In synchronous communications, multiple parties continually listen for and act upon replies from each other. One way to visualize the concept of synchronous communications is to imagine a real-time online chat system designed for a retailer's customer support. The support specialist quickly exchanges messages with the customer to help them track an order, report a missing delivery or inquire about a certain product.
In this scenario, both the sender and receiver establish a communications session. Once the session is established, the two-way conversation takes place with no restrictions on who inputs information when. As one party types and sends a chat message, the party at the other end is present and actively waiting to receive and respond to your message. This is what defines synchronous communications.
<br>
In asynchronous communication, parties do not actively listen for messages. Building off the example above, imagine the customer uses an email support channel instead of the live chat. Asynchronous transmission occurs when the email is sent to the manufacturer's support department. The customer does not expect to receive a reply in real time. Rather, the email message arrives at the retailer, where the staff choose when to read or reply to the message.
<br>
Synchronous execution occurs during online shopping. A user decides to purchase a product, and the system generates a query to determine if inventory is available. The app waits for a response before starting the checkout process. This synchronous design prevents mismatches between inventory and sales.
<br>
Conversely, asynchronous communication allows code to continue to run after it has generated a call or response. Asynchronous communication is particularly valuable for reporting and alerts, such as a manufacturing application that monitors the temperature of an industrial furnace, continually transmits status updates and automatically sends alerts. This type of application should never stop and wait for responses before it moves on to the next action. Instead, the communication alone should trigger either personnel or another application to take action. For instance, the application might send asynchronous temperature updates throughout the day, but also set off a troubleshooting sequence whenever temperatures either exceed or drop below acceptable levels
<br>
