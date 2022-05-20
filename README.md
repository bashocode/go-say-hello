# Go Module Say-Hello

How to create Golang Module

- initial module of go
```
go mod init github.com/{username}/{repository} // let say github.com/bashocode/go-say-hello
```
- initial git
```
git init
git commit -m "initial module say hello"
git remote add origin git@github.com:{username}/{repository}.git
git push -u origin master
```
- add file called sayHello.go
```go
package go_say_hello

func SayHello() string {
	return "Konnichiwa"
}

```
- push to git
```
git add .
git commit -m "add say hello"
git push origin master
```
- add new tag (initiate with v such as v1.0.0 or v1.2.3)
```
git tag v1.0.0
git push origin v1.0.0
```
