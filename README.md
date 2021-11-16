# tri
A todo cli app, made in go

The result of me learning to code my first cli app in go, following the tutorial here:  
https://spf13.com/presentation/building-an-awesome-cli-app-in-go-oscon/

I am currently at slide 159.

The steps to scaffold a cli in go:
- ```go get github.com/spf13/cobra```
- ```cobra init --pkg-name github.com/ltpitt/go-todo-app -a ltpitt```
- ```go mod init github.com/ltpitt/go-todo-app```
- ```go get github.com/spf13/viper```
- ```go build```
- ```tri.exe``` or ```./tri```
