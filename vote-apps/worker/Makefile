build:
	docker build -t worker-builder -f Dockerfile-builder ./
	docker cp $$(docker run -d worker-builder):/code/target/worker-jar-with-dependencies.jar ./

.PHONY: build
