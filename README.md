# HG-Dashboard
$Env:http_proxy="http://127.0.0.1:7890";$Env:https_proxy="http://127.0.0.1:7890"
SET GOARCH=amd64 && SET GOOS=linux && go build
$env:GOOS="linux"; $env:GOARCH="amd64"; go build