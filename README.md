Docker Golang building in go 1.5
-------------------------

## How to use it


#### Using Git

```
	##clone docker file from git
	git clone https://github.com/kkdai/docker-golang.git
	
	##Build docker images
	cd docker-golang
	sudo docker build -t my-go-app .

	##Run docker container
	sudo docker run -it --rm --name my-running-go-app my-go-app

```

## Note:

You will need `rebuild` docker image once your source has changed.


