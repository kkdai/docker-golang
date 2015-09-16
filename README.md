Docker Golang building in go 1.5
---------------

It is a dockerfiler and how to use it to build go 1.5 in docker.

How to use it
---------------

```shell

	##clone docker file from git
	git clone https://github.com/kkdai/docker-golang.git
	
	##Build docker images
	cd docker-golang
	sudo docker build -t my-go-app .

	##Run docker container
	sudo docker run -it --rm --name my-running-go-app my-go-app

```

Note:
---------------
You will need `rebuild` docker image once your source has changed.


License
---------------

This package is licensed under MIT license. See LICENSE for details.