current_dir := $(shell pwd)
.PHONY: build

build:
	sudo docker build -t api-gateway -f Dockerfile .

.PHONY: run

run:
	sudo docker run --rm -p 7000:7000 -it chat-app 

.PHONY: dev

dev:
	sudo docker build -t api-gateway -f Dockerfile . && sudo docker run --rm -p 7000:7000 -it api-gateway