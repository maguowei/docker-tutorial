build:
	GOOS=linux GOARCH=amd64 go build -o hello main.go

build-image:
	docker build -t hello-image .

build-image-rm:
	docker build -t hello-image-rm -f Dockerfile.rm .

run:
	docker run -it --rm hello-image


clean:
	rm -rf hello
	docker rmi hello-image
