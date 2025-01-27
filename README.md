# build
go build hello.go

# test
./hello

# strace
strace -o hello.log ./hello

# strace -T
strace -T -o hello2.log ./hello
