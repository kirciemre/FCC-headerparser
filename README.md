# FCC Request Header Parser Microservice

* A request to /api/whoami should return a JSON object with your IP address in the ipaddress key.

* A request to /api/whoami should return a JSON object with your preferred language in the language key.

* A request to /api/whoami should return a JSON object with your software in the software key.

### Tricky Points :hot_face:

To get the correct ip address, 'x-forwarded-for' must set when the request pass through an HTTP proxy or load balancer.
For more information please visit https://www.rfc-editor.org/rfc/rfc7239#page-6


### What is in req.headers?

req.headers
{
"host":"aea588dc-6d40-4429-a311-194fe44c5429.id.repl.co",
"user-agent":"Mozilla/5.0 (Windows NT 10.0; Win64; x64; rv:95.0) Gecko/20100101 Firefox/95.0",
"accept":"text/html,application/xhtml+xml,application/xml;q=0.9,
image/avif,
image/webp,
*/*;q=0.8",
"accept-encoding":"gzip, deflate, br",
"accept-language":"tr-TR,tr;q=0.8,en-US;q=0.5,en;q=0.3",
"referer":"https://aea588dc-6d40-4429-a311-194fe44c5429.id.repl.co/",
"sec-fetch-dest":"iframe",
"sec-fetch-mode":"navigate",
"sec-fetch-site":"same-origin",
"sec-fetch-user":"?1",
"te":"trailers",
"upgrade-insecure-requests":"1",
"x-forwarded-for":"88.255.88.888",
"x-forwarded-proto":"https",
"x-replit-user-id":"","x-replit-user-name":"",
"x-replit-user-roles":""
}











# [Request Header Parser Microservice](https://www.freecodecamp.org/learn/apis-and-microservices/apis-and-microservices-projects/request-header-parser-microservice)
