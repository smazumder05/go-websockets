Go-Websockets
=============

An implementation of [ Websockets protocol ](http://www.rfc-editor.org/rfc/rfc6455.txt)in [Go](http://golang.org/). The main objective is to learn low level socket programming in Go and familiarize myself with the websockets protocol.

In due course, I plan to use this library in a mobile platform project that I am currently working on.


### Protocol Compliance

Go-WebSockets package will be tested with the server tests in the [Autobahn WebSockets Test
Suite](http://autobahn.ws/testsuite) using the application in the [examples/autobahn
subdirectory](https://github.com/gorilla/websocket/tree/master/examples/autobahn).

### Go-WebSocket Features

<table>
<tr>
<th></th>
<th><a href="https://github.com/smazumder05/go-websockets">Go-Websockets</a></th>
<th><a href="http://godoc.org/code.google.com/p/go.net/websocket">go.net</a></th>
</tr>
<tr>
<tr><td>Protocol support</td><td>RFC 6455</td><td>RFC 6455</td></tr>
<tr><td>Limit size of received message</td><td>Yes</td><td>No</td></tr>
<tr><td>Send pings and receive pongs</td><td>Yes</td><td>No</td></tr>
<tr><td>Send close message</td><td>Yes</td><td>No</td></tr>
<tr><td>Read message using io.Reader</td><td>Yes</td><td>No, see note</td></tr>
<tr><td>Write message using io.WriteCloser</td><td>Yes</td><td>No, see note</td></tr>
<tr><td>Encode, dec
