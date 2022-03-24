# C2-Traffic Redirection
Because we dont't want to use (directly) our external IP-adress for C2-server listeners, 
we can use redirector instances in aws, azure etc. to redirect the C2-traffic to our (internal) C2-server. 
There are several different commands which can be used in a linux redirector to redirect traffic:
- socat 
- iptables 
