build:
	GOOS=linux GOARCH=amd64 go build -o hello main.go

build-image:
	docker build -t hello-image . -f Dockerfile.scratch

run:
	docker run -it --rm hello-image


clean:
	rm -rf hello
	docker rmi hello-image
