# Advanced Topic

## Stateless
* State = Current Situation(in context)
* State(HTTP) = Web Request and Response.
* HTTP Stateless = Request Unknown.
* HTTP is stateless(No tiene estado) by Default.
* HTTP methods = REST and SOAP. 
* REST and SOAP are stateless by default. 
* REST = Representational State Transfer. 
* SOAP = Simple Object Access Protocol. 
* Stateful = File Transfer Protocol(FTP)


How do applications "remember"?
**Cookies**. 

## COOKIES

It is a piece of information. 

It are set on HEADERS LINES.
* HTTP HEADER: Set-Cookie.

## HTTP Security

* Cookies are not executable. 
* Cookies don't store passowords. (e.g. can use tokens)
* Applications store data with session_id. 
* Punishment. 
* Multi-factor Authentication. 
* Changes(e.g. biometrics).
* Antivirus Software. 
* Human error. 
* Be Proactive. 


## HTTP Infrastructure (Hardware and Software)

-| No HTTP(e.g telephone from 80s)| HTTP(e.g Amazon)|
---|---|---|
Application|Bell|Amazon
Client(Requester)|Person calling| Browser, Programs|
Initial Receiver|Telephone|Load Balancer|
Server|Person answering| Application Server|
Client-Server Connection|Copper wires|Cables or Satellite|
Memory| Brain of person answering|Database|

## Stateless Infrastructure Benefits

* Scalability. 
* Resilience (Crashability)
* Less Memory Needed. 
