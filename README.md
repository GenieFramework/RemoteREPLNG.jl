# RemoteREPLNG (New Generation)

`RemoteREPLNG` allows you to connect your local julia REPL to a separate Julia
process and run commands interactively:

* Run code in the `Main` module of a remote Julia process
* Standard REPL tab completion and help mode with `?`
* Transfer variables between processes with `@remote`
* Automatic ssh tunnel for network security. Reconnects dropped connections.

## Demo

[<img src="https://asciinema.org/a/670195.svg" width=50%>](https://asciinema.org/a/670195)

