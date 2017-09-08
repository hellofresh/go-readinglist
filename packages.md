# Packages

This page contains packages recommended by HelloFresh Golang Clan. These are not just the cool repos around, but the packages that we found really practical and worth to use over the others.

If you need more packages or just for inspiration, visit [Awesome Go](https://awesome-go.com/).

## Configuration

- [github.com/kelseyhightower/envconfig](https://github.com/kelseyhightower/envconfig) - get configs from environment variables

## Database

- [database/sql](https://golang.org/pkg/database/sql/) - standard SQL library that you should stick to or build upon
- [github.com/jmoiron/sqlx](https://github.com/jmoiron/sqlx) - extension to standard SQL library that makes it a bit more convenient
- [github.com/mattes/migrate](https://github.com/mattes/migrate) - database migrations

## Forms

- [github.com/gorilla/schema](https://github.com/gorilla/schema) - decode forms and urls into Go structs and vice versa

## HTTP

- [github.com/go-chi/chi](https://github.com/go-chi/chi) - router with decent performance and middleware support
- [github.com/dgrijalva/jwt-go](https://github.com/dgrijalva/jwt-go) - JSON Web Token library
- [github.com/hellofresh/health-go](https://github.com/hellofresh/health-go) - adds health status check endpoints to your app
- [github.com/rafaeljesus/retry-go](https://github.com/rafaeljesus/retry-go) - retry mechanism to build into your HTTP clients
- [github.com/sony/gobreaker](https://github.com/sony/gobreaker) - CircuitBreaker implementation, use this in your HTTP clients


## Logging and Metrics

- [github.com/sirupsen/logrus](https://github.com/sirupsen/logrus) - logging package
- [github.com/hellofresh/logging-go](https://github.com/hellofresh/logging-go) - HelloFresh extensions to Logrus
- [github.com/hellofresh/stats-go](https://github.com/hellofresh/stats-go) - collect and push metrics

## Testing

- [github.com/DATA-DOG/godog](https://github.com/DATA-DOG/godog) - Cucumber-style BDD testing
- [github.com/stretchr/testify](https://github.com/stretchr/testify) - makes assertions and mocking more convenient

## Validation

- [github.com/asaskevich/govalidator](https://github.com/asaskevich/govalidator) - validation package that uses struct tag annotations
