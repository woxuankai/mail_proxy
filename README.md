# mail reverse proxy

# IMAP

# SMTP
## flow chart
### ehlo or helo
1. check domain and public ip address, pass 127.0.0.1 and localhost

### Authentication
1. Authentication is compulsory in prevention of abuse.
1. (Optional) Only users in the whilelist is allowed in prevention of abuse.
1. Tcp connection to server will be established after authentication.
