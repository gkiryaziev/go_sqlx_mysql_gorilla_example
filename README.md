## Golang/Gorilla + MySQL/SQLX Example

[![Go Report Card](https://goreportcard.com/badge/github.com/gkiryaziev/go-gorilla-mysql-sqlx-example)](https://goreportcard.com/report/github.com/gkiryaziev/go-gorilla-mysql-sqlx-example)

An example of how we can organize work with [sqlx](http://jmoiron.github.io/sqlx/) and [MySql](https://www.mysql.com/)
in [Golang/Http](https://golang.org/) and [Gorilla](http://www.gorillatoolkit.org/pkg/mux) web toolkit.

Also used [Negroni](https://github.com/codegangsta/negroni) HTTP Middleware and [Angular.js](https://angularjs.org/)
MVW Framework for frontend.

### Used libraries and frameworks:
```
1. Gorrila
2. Negroni
3. Sqlx
4. Angular.js
```

### Install:
```
go get -u github.com/gkiryaziev/go-gorilla-sqlx
```

### Edit configuration
```
Copy `config.default.yaml` to `config.yaml` and edit configuration.
```

### Build and Run:
```
go build && go-gorilla-sqlx
```

### Packages:
You can use [glide](https://glide.sh/) packages manager to get all needed packages.
```
go get -u -v github.com/Masterminds/glide

cd go-gorilla-sqlx && glide install
```