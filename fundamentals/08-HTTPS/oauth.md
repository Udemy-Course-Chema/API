# OAuth 

Search: RFC Note 6749

Stand for "Open Authorization". 


* OAuth allows a 3rd Party Access
* Limited(authorized) access. 
* To a web service(HTTP).
* OAuth 1.0 obsolete. 


Roles:
* Resource Owner
* Resource Server
* Client/Application (Third party Application)
* Authorization Server. 

 

## Protocol Flow, in order:

1. Client -> Authorization Request -> Resource Owner
2. Client <- Authorization Grant <- Resource Owner.
3. Client -> Authorization Grant -> Auth Server
4. Client <- Access Token <- Auth Server. 
5. Client -> Access Token -> Resource Server. 
6. Client <- Protected Resource <- Resource server. 

## Authorization Grant Types

* Authorization Code (MOST USED)*
* Implicit (Ajax, JavaScript)
* Resource Owner 
* Client Credentials

## ACCESS TOKEN - REFRESH TOKEN

Refresh token -> used a new access token. 

String Format, Binary Format. 



     