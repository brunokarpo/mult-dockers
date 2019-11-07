dev-build:
	docker image build -f Dockerfile.dev -t brunokarpo/multiple-dockers-client .

dev-run: dev-build
	docker container run --rm -p 3000:3000 brunokarpo/multiple-dockers-client