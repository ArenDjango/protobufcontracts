# Protobuf contracts for all microservices

## Generate protobuf

### auth-service
`protoc -I auth-service auth-service/auth_service.proto --go_out=./gen/go/auth-service --go_opt=paths=source_relative --go-grpc_out=./gen/go/auth-service/ --go-grpc_opt=paths=source_relative`

### routeguide