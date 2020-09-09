build:
	docker build -t languagesensation/hiring:latest .

run:
	docker run --restart=always --name hiring -d -p 80:80 languagesensation/hiring:latest

clean:
	docker rm -f hiring