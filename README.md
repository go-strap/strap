<!-- @format -->

# **go-strap (Coming Soon)**

Hello! I'm new to Go development. **go-strap** is something I've developped (mostly for myself) to "bootstrap" Go apps for use as a back-end server for front-end web apps. It's been a good learning experience. Collaboration and usage is encouraged, subject to the [open source MIT license](https://github.com/go-strap/strap/blob/main/LICENSE). Happy coding!

## Features

**go-strap** provides quick set-up of a "bootstrapped" Go app that has an HTTP server, router, database, logging, build and deployment scripts, documentation, and tests. You can use as much or as little of the bootstrapping as you want.

- [net/http](https://pkg.go.dev/net/http#hdr-Servers) server, using [Gin](https://github.com/gin-gonic/gin) as the router by default
- [slog](https://pkg.go.dev/golang.org/x/exp/slog) logging by default
- [errgroup](https://pkg.go.dev/golang.org/x/sync/errgroup) go routine synchronization
- [os.Signal](https://pkg.go.dev/os/signal) (e.g. CTRL+C) handling
- Graceful error handling, server shutdown, and db disconnect

This project tries to adhere to the [Standard Go Project Layout](https://github.com/golang-standards/project-layout).

More details to come as I actually build this thing...
