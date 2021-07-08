FROM golang:alpine
LABEL maintainer="Evans Doe Ocansey"

WORKDIR /go/src/app
ADD . .
RUN go mod init
RUN go build -o helloworld
EXPOSE 6111
# Command to run on container start
CMD [ "./helloworld" ]

