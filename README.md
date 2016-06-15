# Chatroom
A simple chatroom demo from [this talks](https://talks.golang.org/2012/chat.slide) implemented by websocket.
Chatroom will match up every two person who enter this website.
It can support multiple chatting simultaneously benefit from Go's concurrent feature:
- goroutine
- channel

## Install
First, install [Go](https://golang.org/)
Then,
```bash
go get github.com/ladrift/chatroom
```
and run
```bash
$GOPATH/chatroom
```
Go to visit `http://localhost:4000` in your browser.
You can open two windows to simulate two chatting persons.

## License
MIT
