SSH Utility


This is a tool to assist me with managing my different remote clients (Raspberry Pi's)

It will use a yaml config file to assign a host name, user, password, ipaddress, friendly name

I found that trying to control the connection within go and auto enter the password was overkill so it will preview what the password is prior 
to starting the connection

**
TODO

Add password hashing (enter a master password to unlock)
Add ability to update device record (sshelp --update pi3) as example would ask for verify / change values