current_dir := $(shell pwd)
.PHONY: build

build:
	sudo docker build -t chat-app -f Dockerfile .

.PHONY: run

run:
	sudo docker run --rm -p 7001:7001 -it chat-app 

.PHONY: dev

dev:
	sudo docker build -t chat-app -f Dockerfile . && sudo docker run --rm -p 7001:7001 -it chat-app