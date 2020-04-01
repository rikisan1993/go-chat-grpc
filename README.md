# Chat app using gRPC
simple terminal chat app broadcaster using golang and gRPC

### Run the server
```
go run main.go
```
the server will listen to localhost:8080


### Run the client
```
go run client/main.go
```

the client by default will connect to localhost:8080, and user `Anon` for anonymous as default user, use `-N` flag to use another username.

### Sending message
just type anything and hit enter after running the client


### Spin up server as container
```
docker build -t [your_image_name]:[your_tag] .
```

replace `[your_image_name]` with any image name you want, and `[your_tag]` with any tag you need


### Disclaimer
this project is a follow-along code exercise based on [tutorial](https://www.youtube.com/watch?v=mML6GiOAM1w&list=PLlwUM8JwEjmoxhCxHia75uA7-fJI2HoiT) by [Tensor Programming](https://www.youtube.com/channel/UCYqCZOwHbnPwyjawKfE21wg) on Golang with gRPC and Docker.
