## AS-http-status-codes

# HTTP response status codes
## What are HTTP status codes?
An HTTP status code is a server response to a browser’s request. When you visit a website, your browser sends a request to the site’s server, and the server then responds to the browser’s request with a three-digit code: the HTTP status code.

These status codes are the Internet equivalent of a conversation between your browser and the server. They communicate whether things between the two are A-okay, touch-and-go, or whether something is wrong. Understanding status codes and how to use them will help you to diagnose site errors quickly to minimize downtime on your site. You can even use some of these status codes to help search engines and people access your site;  a 301 redirect, for example, will tell bots and people that a page that has moved somewhere else permanently.

The first digit of each three-digit status code begins with one of five numbers, 1 through 5; you may see this expressed as 1xx or 5xx to indicate status codes in that range. Each of those ranges encompasses a different class of server response.

1. [Informational responses](/AS-http-status-codes/#information-responses) (100 – 199)
2. [Successful responses](/AS-http-status-codes/#successful-responses) (200 – 299)
3. [Redirection messages](/AS-http-status-codes/#redirection-messages) (300 – 399)
4. [Client error responses](/AS-http-status-codes/#client-error-responses) (400 – 499)
5. [Server error responses](/AS-http-status-codes/#server-error-responses) (500 – 599)


## Information responses
[`100 Continue`](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/100)

[`101 Switching Protocols`](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/101)

[`102 Processing`](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/102)

[`103 Early Hints`](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/103)


## Successful responses

[`200 OK`](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/200)

[`201 Created`](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/201)

[`202 Accepted`](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/202)

[`203 Non-Authoritative Information`](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/203)

[`204 No Content`](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/204)

[`205 Reset Content`](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/205)

[`206 Partial Content`](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/206)

[`207 Multi-Status`](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/207)

[`208 Already Reported`](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/208)

[`226 IM Used`](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/226)


## Redirection messages

[`300 Multiple Choices`](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/300)

[`301 Moved Permanently`](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/301)

[`302 Found`](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/302)

[`303 See Other`](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/303)

[`304 Not Modified`](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/304)

[`305 Use Proxy`](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status#305_use_proxy)

[`306 unused`](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status#306_unused)

[`307 Temporary Redirect`](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/307)

[`308 Permanent Redirect`](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/308)


## Client error responses

[`400 Bad Request`](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/400)

[`401 Unauthorized`](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/401)

[`402 Payment Required`](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/402)

[`403 Forbidden`](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/403)

[`404 Not Found`](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/404)

[`405 Method Not Allowed`](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/405)

[`406 Not Acceptable`](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/406)

[`407 Proxy Authentication Required`](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/407)

[`408 Request Timeout`](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/408)

[`409 Conflict`](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/409)

[`410 Gone`](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/410)

[`411 Length Required`](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/411)

[`412 Precondition Failed`](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/412)

[`413 Content Too Large`](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/413)

[`414 URI Too Long`](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/414)

[`205 Reset Content`](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/205)

[`415 Unsupported Media Type`](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/415)

[`416 Range Not Satisfiable`](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/416)

[`417 Expectation Failed`](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/417)

[`418 I'm a teapot`](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/418)

[`421 Misdirected Request`](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/421)

[`422 Unprocessable Content`](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/422)

[`423 Locked`](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/423)

[`424 Failed Dependency`](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/424)

[`425 Too Early`](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/425)

[`426 Upgrade Required`](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/426)

[`428 Precondition Required`](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/428)

[`429 Too Many Requests`](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/429)

[`431 Request Header Fields Too Large`](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/431)

[`451 Unavailable For Legal Reasons`](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/451)


## Server error responses

[`500 Internal Server Error`](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/500)

[`501 Not Implemented`](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/501)

[`502 Bad Gateway`](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/502)

[`503 Service Unavailable`](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/503)

[`504 Gateway Timeout`](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/504)

[`505 HTTP Version Not Supported`](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/505)

[`506 Variant Also Negotiates`](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/506)

[`507 Insufficient Storage`](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/507)

[`508 Loop Detected`](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/508)

[`510 Not Extended`](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/510)

[`511 Network Authentication Required`](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status/511)
