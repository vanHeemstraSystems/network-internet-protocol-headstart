network-internet-protocol-headstart
# Network Internet Protocol (NIP) - Headstart

Based on "nip.io" at https://nip.io/

"Dead simple wildcard DNS for any IP Address."

In short, you can make your public IP address of your workstation or server browseable by postfixing it with "nip.io".

For example:

Your local IP (say 217.103.138.72) is public (seen from Internet), but will have a URL entrypoint (here: 217.103.138.72.nip.io) which means it is accessible from the Internet (or other public networks) as a web service. Great for testing a website that is running locally, from a public URL for example.

**Tip**: Use Google to search "What's my IP" which will find your public IP address (here: 217.103.138.72). If you have a local web server or load balancer running at say the default port 80, you can browse to it by following http://217.103.138.72.nip.io

See how to use it at "[How to manage Kubernetes & containers with Portainer](https://youtu.be/FC8pABzxZVU?t=1093) - starting at 18:10" 
