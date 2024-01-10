### server.go

* listens on port 8090 http
* called like this:
* http://localhost:8090/hello?name=world
* both CodeBuild and CodeDeploy write-to and read-from, respectively, this s3 bucket:
* https://us-east-2.console.aws.amazon.com/s3/buckets/gohello-code-deploy/?region=us-east-2
