- https://stackoverflow.com/questions/57885949/private-repo-go-1-13-go-mod-failed-ping-sum-golang-org-lookup-ver/57887036#57887036 (private Golang git repo)
- https://golang.org/src/crypto/x509/example_test.go (x509 certs code examples)

## Naming

- https://talks.golang.org/2014/names.slide#1
- https://golang.org/doc/effective_go.html#names
- https://blog.golang.org/package-names


## Style

- https://github.com/golang/go/wiki/CodeReviewComments


## Web dev general

- https://stackoverflow.com/a/11468132 (Nested html/template)


## Useful libraries

- https://github.com/Go-SQL-Driver/MySQL/
- https://github.com/DATA-DOG/go-sqlmock
- http://www.gorillatoolkit.org/
- https://github.com/stretchr/testify


## database/sql

- http://go-database-sql.org/errors.html


## Lists

- https://github.com/guardrailsio/awesome-golang-security


## Quick refresher guides

- https://yourbasic.org/golang/
- https://gobyexample.com


## Fundamentals

- https://yourbasic.org/golang/slices-explained/
- https://yourbasic.org/golang/find-search-contains-slice/ (`sort.SearchInt`, `sort.Search`)
- https://www.geeksforgeeks.org/how-to-compare-equality-of-struct-slice-and-map-in-golang/
- https://blog.golang.org/context
- https://blog.golang.org/pipelines
- https://stackoverflow.com/a/49831018 (Order of initialization: imports, constants, vars, `init` functions)
- https://golangdocs.com/init-function-in-golang (Multiple `init` functions can be in same file and run in order of definition)


## Practices

- https://www.youtube.com/watch?v=29LLRKIL_TI (7 Common mistakes in Go and when to avoid them by Steve Francia)
- https://www.youtube.com/watch?v=rWBSMsLG8po (How I write HTTP web services after 8 years - Matt Ryer)
- https://www.youtube.com/watch?v=MeOK1UzGHYw (Example of a small proxy in Go; can just look at https://github.com/zorkian/lca2015/blob/master/part5/main.go)
- https://github.com/cristaloleg/go-advice


## Testing

- https://blog.lamida.org/mocking-in-golang-using-testify/
- https://stackoverflow.com/questions/19167970/mock-functions-in-go


### Mocking

- https://github.com/golang/mock
- https://github.com/vektra/mockery
- https://github.com/smartystreets/goconvey (Organizing tests; there's web UI)
- https://github.com/alicebob/miniredis
- https://medium.com/agrea-technogies/mocking-dependencies-in-go-bb9739fef008


## Concurrency Patterns

- https://medium.com/@thejasbabu/concurrency-patterns-golang-5c5e1bcd0833 (good summary)
- https://blog.golang.org/pipelines
- https://dzone.com/articles/visualizing-concurrency-in-go-1
- https://www.oreilly.com/library/view/concurrency-in-go/9781491941294/ch04.html


## Profiling

- https://blog.golang.org/pprof


## CGo

- https://golang.org/cmd/cgo/#hdr-Passing_pointers (Cannot pass Go pointers to C; what makes a pointer a Go pointer)
