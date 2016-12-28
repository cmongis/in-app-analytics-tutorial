# In-house usage reporter
This tutorial describe a way to implement a service that will be incorporated into a Java app and will send usage report to a Node.js distant server for later analysis.

## Motivation
I needed some in-app analytic for a project I was working on but I didn't want to pay for a in-app analytic solution. Since the app already had a Update Server, I decided to update the server in order to gather usage statistics that can be later on analysed.

## Technical goal

I needed to know which button the user click, or which window they open, or hover, or which value they set for certain form in order to be able to highlight common behaviour or detect ignore UI elements and improve the software


## Technology used

### For the client

- Java 8
- WebSocket.IO client
- RXJava to deal with asynchronous request

### For the server
 
- NodeJS Socket.IO
 
