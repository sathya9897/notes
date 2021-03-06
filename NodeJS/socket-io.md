# Socket.io

* By default socket's connect to `/` namespace
* In socket.io you can have multiple namespaces and each namespace can have multiple rooms
* To use a specific namespace we can use `const chatspace = io.of("/chat")` now we use `chatspace` which holds reference to chat namespace to emit or listen to events.
* 