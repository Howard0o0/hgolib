## install go in mac

**DO NOT INSTALL GO BY BREW!**

1. set GOPATH  
```
vi ~/.bashrc
export GOPATH=$HOME/work/go
```

2. install go.pkg

## solve go get problem

touch main.mod in project folder  

check go env and  
```
$ go env -w GO111MODULE=on
$ go env -w GOPROXY=https://goproxy.io
```


