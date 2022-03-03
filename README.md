# grpc-fc

Command to generate the stubs:
protoc --proto_path=proto proto/*.proto --go_out=pb

Command to generate _grpc:
protoc --proto_path=proto proto/*.proto --go_out=pb --go-grpc_out=pb