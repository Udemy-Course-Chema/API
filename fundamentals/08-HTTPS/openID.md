# OPENID 

Advanced topic 2.0

OAuth Protocol Flow

1. client -> auth request -> resources Owner.
2. client <- Auth Grant <- R.O.
3. client -> Auth Grant -> Auth Server
4. client <- Access Token + ID Token <- Auth Server
5. client -> Access Token + ID Token -> Resource Server. 
6. client <- Protected Resource <- Resource Server. 