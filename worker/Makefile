dev-build:
	docker image build -f Dockerfile.dev -t brunokarpo/multiple-dockers-worker .

dev-run: dev-build
	docker container run --rm brunokarpo/multiple-dockers-worker