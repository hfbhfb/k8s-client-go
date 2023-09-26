
ImageVersion=v0.0.2

all:
	export GOOS=linux && export GOARCH=amd64 &&go build
	docker build -t hefabao/ckad-aaa:${ImageVersion} .
	echo "all"
