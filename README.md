# bookish-computing-machine
Setting up an Nginx web server with Railgun

- Build up a web server (nginx) to serve a landing page.
- Make the web server available over IPv6 **only**
- Setup Railgun; confirm Railgun is working correctly
- Obtain an elliptic curve certificate (self-signed is okay) and install it on your web server. 
- Force all requets to your web server over SSL, e.g., HSTS and PageRules.
- Display / compare the two HTTP response headers -- going through Cloudflare and an HTTP request going directly to your server -- by writing a small script to compare the headers.


**TODO May 2019** Update this repo with 
- your multi-page write-up on setting up an NGINX server
- be sure to highlight all the security lockdowns that you implemented so that your virtualized machine in the cloud didn't get pwned (also show that on the lesser-secured box - login was only password protected, no ssh key - that the box got pwned within 10 minutes)
- configuring Railgun (also explain how it works in terms of only serving up the page content delta which improves loading time)
- [UWF (Uncomplicated Firewall)](https://wiki.ubuntu.com/UncomplicatedFirewall) setup that you did
- be sure to explain the design decision to use `memcached` and the performance boost you got from that (protip: set debugging level to 3 - literally picked that at random; it seemed probably high enough to provide something useful)
