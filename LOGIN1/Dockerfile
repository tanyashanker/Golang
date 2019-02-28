FROM golang:1.11

# Add Maintainer Info
# Set the Current Working Directory inside the container
WORKDIR $GOPATH/src/app

ADD src src

CMD [ "go", "run", "src/main.go" ]

