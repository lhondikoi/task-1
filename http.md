# Difference between HTTP 1.1 and HTTP 2.0
HTTP 1.1 | HTTP 2.0
-|-
It was introduced in the year 1997. | It was introduced in the year 2015
Allows sending of a single request at a time | Allows sending of requests and receiving of responses asynchronously
Loads resources one after the other. If one resource cannot be loaded, the resources behind it are blocked. | Multiplexing: Multiple streams of data can be sent at once, which ensures that no one resource can block another resource.
Request prioritization is not supported. | Request prioritization: Allows numeric prioritization in a batch of requests.
Server can send a response only after receiving a request from the client. | Server push: Server can send resources to the client before the client sends a request. 