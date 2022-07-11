Understanding What is HTTP

(.)HTTP stands for Hyper Text Transfer Protocol
(.)WWW is about communication between web clients and servers
(.)Communication between client computers and web servers is done by sending HTTP Requests and receiving HTTP Responses

HTML uses Tags like <head>,<body>,<title>,<p>,etc for different functionalities.
For EG consider the below code,
<!DOCTYPE html>
<html>
  <head>
    <title>Hi!</title>
  </head>
  <body>
    <p>Hello world!</p>
  </body>
</html>

Understanding what is HTTP1.1

HTTP 1.1 is a version of Hypertext Transfer Protocol (HTTP), the World Wide Web application protocol that runs on top of the Internet's TCP/IP suite of protocols. HTTP 1.1 provides faster delivery of Web pages than the original HTTP and reduces Web traffic. Developed by a committee of the Internet Engineering Task Force (IETF) that includes the Web's chief creator Tim Berners-Lee, HTTP 1.1 is supported by the latest Web servers and browsers.
	
What is HTTP2
	
HTTP/2 is the second version of the HTTP protocol aiming to make applications faster, simpler, and more robust by improving many of the drawbacks of the first HTTP version.

The primary goals of HTTP/2 are:

(*)Enable request and response multiplexing
(*)Header compression
(*)Compatibility with the methods, status codes, URIs, and header fields defined by the HTTP/1.1 standard
(*)Optimized prioritization of requests, making sure that loading for optimal user experience is as fast as possible
(*)Support for server-side push
(*)Server-side backwards compatibility, making sure servers can still serve clients only supporting HTTP/1.1 without any changes
(*)Transforming to a binary protocol from the text-based HTTP/1.1
	
The history of HTTP/1.1 to HTTP/2

(*)In 1989, Sir Timothy John Berners-Lee invented the HTTP protocol on a NeXTcube workstation with a 25 MHz CPU and several MBs of RAM. The protocol worked on networks with port connection speeds of 10 Mbits. Today, however, we have dramatically faster CPUs and thousands of MBs of RAM, but the main WWW protocol is still only HTTP/1.1. It was last updated in 1992, so why are we still using it?
(*)While other protocols have been updated over the years, HTTP/1.1 has not changed and has developed many issues with speed and security, and user-friendliness as a result.
(*)Google was the first to investigate issues with HTTP/1.1. At the time, they were spending millions of dollars a year to support their data centers, and the HTTP/1.1 protocol simply cost too much in terms of CPU resources and internet connection capacity. They developed SPDY as an experimental alternative to HTTP/1.1—a protocol designed for better security and improved page load times.
(*)The HTTP Working Group of the Internet Engineering Task Force (IETF) investigated Google’s SPDY protocol and Microsoft’s equivalent when designing the next version of HTTP. Facebook recommended HTTP/2 to be based on SPDY in July 2012.
(*)Based on the research done by Google, Microsoft, and Facebook, the IETF released the HTTP/2 protocol in 2015. This became the second major version of the most useful

HTTP/2 Features
	
(*)Binary: Uses 0's and 1's.
(*)Multiplex: Permits multiple requests.
(*)Compression: Uses effective compression techniques.
(*)Stream prioritization: Allows exchange of successive streams.
(*)Server push: The server can send additional information.
(*)Increased security: HTTP/2 is supported through encryped connections.
	
So they reason why they shifted to HTTP2 was because of major cost cuts, more reliable, flexible and has enhanced speed. Its like a network on is on HTTP1.1 but with drugs.
