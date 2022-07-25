Refer: https://codeforces.com/blog/entry/105252

In order to add languages to CF-Tools(C++20 64bit and C++17 64bit), Replace the langs.go inside the client folder with the given lang.go file. and then recompile the file with the following command(remember to be on the main directory, ie: cf-tool):

go build -ldflags "-s -w" cf.go
