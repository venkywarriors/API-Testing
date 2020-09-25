# API-Testing

![alt text](https://miro.medium.com/max/723/1*OICaHvjcxhpFofj6Bai6aA.jpeg)

RestSharp is a comprehensive, open-source HTTP client library that works with all kinds of DotNet technologies.  It can be used to build robust applications by making it easy to interface with public APIs and quickly access data without the complexity of dealing with raw HTTP requests.

[RestSharp Basics](https://github.com/venkywarriors/API-Testing/blob/master/RestSharp-3.pdf) <br>
[RestSharp Vs RestAssured](https://github.com/venkywarriors/Restshap-with-c-sharp/blob/master/RestSharp%20Vs%20RestAssured.pdf)<br>
[Rest Vs SOAP](https://github.com/venkywarriors/Restshap-with-c-sharp/blob/master/soap%20and%20rest_removed.pdf)<br>

### How to write JSONPath expressions
JSONPath is a query language for JSON, similar to XPath for XML. AlertSite API endpoint monitors let you use JSONPath in assertions to specify the JSON fields that need to be verified.<br>
<a href="https://support.smartbear.com/alertsite/docs/monitors/api/endpoint/jsonpath.html">JSONPath notation</a><br>
<a href="https://docs.hevodata.com/pipelines/miscellaneous/how-to-write-jsonpath-expressions/">JSONPath Syntax</a><br>

### How to Use Base 64 Encoding in Header 
The auth code and client credentials grants require the auth code to be passed in the Authorization header using base 64 encoding. Many HTTP/REST libraries will handle the formatting and encoding for basic authentication requests, though not all do. This page serves to provide an explanation of the encoding process.
#### The Authorization Header
The Authorization header is the format Authorization: Basic encodedString, where encodedString is the result of base 64 encoding the OAuth client's values as clientId:clientSecret.<br>
<a href="https://docs.smsportal.com/docs/rest-examples">Base 64 Encoding</a><br>
