## Invoke Lambda versions

aws lambda invoke --function-name mytestfunctionn:\$LATEST response.json

aws lambda invoke --function-name mytestfunctionn:1 response.json

## Invoke Lambda alias

aws lambda invoke --function-name mytestfunctionn:myapp response.json
