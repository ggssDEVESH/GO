# GO

## go launguage

4 layers
1 storage
2.service layer - 1 micro service should take care of one resposiblity.
we do that using interface. struct --> many interfaces.
3.go uses composition instead of inheritance.
4.dependecy inversion --> use interface as type for the struct.
5.service layer have one interface. inside multi methods.
6.we need to use sigleton patteren. we should create a db such that it is should have interface.
7.service it will have one interface, one struct of the interface type. in service layer.
8.if you add logging, auth you can embaded into the core struct and pass as a dependecy.
9.transport layer. we can create multiple servers which will work as multi threading.

file .go extenstion
go mod init --> to initialize go
go run . to run
go get <package name>
go mod tidy --> to remove unused variable.
