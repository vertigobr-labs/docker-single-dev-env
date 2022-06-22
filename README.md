# single-dev-env
Example used to try a single container sample of Docker Dev Environments

## Run the application
You can simply use `make run` command or do it yourself with `go run main.go`

Those commands will start a http server listening on port `8080` 
and if your request `http://localhost:8080` you'll see the following output: 
```shell
❯ curl http://localhost:8080

          ##         .
    ## ## ##        ==
 ## ## ## ## ##    ===
/"""""""""""""""""\___/ ===
{                       /  ===-
\______ O           __/
 \    \         __/
  \____\_______/


Hello from Docker!

```

## Hot reloading
You can simply use `make dev` command to run the application with hot reloading changes.

Or do it yourself manually:

```sh
go get github.com/pilu/fresh # once
fresh
```
