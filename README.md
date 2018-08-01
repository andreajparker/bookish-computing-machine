# bookish-computing-machine
Setting up an Nginx web server with Railgun

- Build up a web server (nginx) to serve a landing page.
- Make the web server available over IPv6 **only**
- Setup Railgun; confirm Railgun is working correctly
- Obtain an elliptic curve certificate (self-signed is okay) and install it on your web server. 
- Force all requets to your web server over SSL, e.g., HSTS and PageRules.
- Display / compare the two HTTP response headers -- going through Cloudflare and an HTTP request going directly to your server -- by writing a small script to compare the headers.
