# HTTP
HyperText Transfer Protocol 
The web page is made up of hyper text language and the http protocol(rules and regulation) used for the communication between client(browser) and servers(cloud computers).
client sends HTTP requests(www.google.com) and the server receives request and returns the HTTP response as an web page,images,video etc. to the browser.
After the response the communication is end and have to create new communication. 
# History
Tim Berners-Lee build a hypertext system over the internet in  1990. 
A textual format to represent hypertext documents, the HyperText Markup Language (HTML).
A simple protocol to exchange these documents, the HypertText Transfer Protocol (HTTP).
Methods:
GET - Requesting the server to send the data.(web page)
POST - client giving request to store the data in server.(username and password)
# Evolution
##HTTP O.9 
    -Only GET method by the path(GET/index.html). Only html file can be transmitted and no other documents.
##HTTP 1.o
    - HTTP headers is introduced. It can transmit other files also and requesting image has been made. Open the communicaton by requesting and ending the connection after response and for getting another data have to open new connection.
New TCP connection with each request(slower).
##HTTP 1.1
    - The connection will not lost after the response from the server they will try to keep them alive. Allowing to send a second request before the answer for the first one is fully transmitted.
##HTTP/2
    -Multiplicity - sending multpile request in one request and speeding.
##HTTP/2 over QUIC (HTTP/3)
     - replacing TCP with UDP for speed but the data can be lost. it is in experimental till now.
