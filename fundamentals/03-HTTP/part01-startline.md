# Start Line

Request and response are not the same. 

_|Request|Response|
-----|-----|-----|
Name|Start Line, Request Line| Start Line, Response Line, Status Line|
HTTP Version | HTTP/1.1 | HTTP/1.1|
Method?| Get, Post, Put, Delete, etc.| None|
Need API Program Folder Location?| Yes(example: /search) | None |
Parameters?| Yes, example: ?search=helloWorld | None |
Status Code | No | Yes(200,300,400,500)|
Format | Method(space) API Program Folder Location+Parameters(space)HTTP Version| HTTP Version + Status Code| 
Example| GET/search?q=HelloWorld HTTP/1.1 | HTTP/1.1 200 OK |


## Idempotence
Can do as many times as you want and result statys the same. 
In other words, "safe" to repeat.

Method|idempotent?(Safe to repeat), can we repeat?|
---|---|
GET| Yes|
POST| No|
PUT| Yes|
DELETE|Yes|



What is in the request HTTP start line? 
1. Method.
2. API Program Folder(optional).
3. Parameter(s) (optional).
4. HTTP/1.1



