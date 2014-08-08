# Can godep support this?

## Instructions
```
git clone https://github.com/rliebling/godep_example
cd godep_example
export GOPATH=$PWD
cd src/
godep save github.com/rliebling/main
##### OR....
cd github.com/rliebling/main
godep save
```

Whatever i do, i seem to get this error:
```
godep: directory "/home/rich/dev/godep_example/src" is not using a known version control system
```
Note that the .git dir lives in /home/rich/dev/godep_example


