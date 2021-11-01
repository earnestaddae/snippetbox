## Git clone built with Go

Exploring an alternative for developing web application with Go

### Features

- Dynamic HTML templates
- Middleware
- Database management with mySQL
- RESTFul Routing
- Session Managment
- User Authenitcation & Authorization
- Testing [unit, end-to-end, integration]
- Security with improvement with CSRFToken
- HTTP & HTTPS
- Self-signed certificate for TLS

### Application

- A minimal clone of [Pastebin](https://pastebin.com/) or [Gist](https://gist.github.com/discover)

### Third-party Packages

- [Alice](https://github.com/justinas/alicego) for middleware management
- [Golang session](https://github.com/golangcollege/sessions) for session management
- [Pat](https://github.com/bmizerany/pat) for routing

### Tech Stack

- Go v 1.17.2
- MySQL
- HTML
- CSS

### How to Run app

- Install go
- Setup database and make sure it is running
- Change database store name, in `main.go`
- Run `go run ./cm/web`
- Visit `https:localhost:4000`
