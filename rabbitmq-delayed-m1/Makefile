DOCKERNAME=mandaputtra/rabbitmq-delayed-m1
VERSION=20230214

build:
	docker build -f Dockerfile -t $(DOCKERNAME):$(VERSION) .

push: build
	docker push $(DOCKERNAME):$(VERSION)
