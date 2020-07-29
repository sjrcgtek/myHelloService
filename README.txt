SJR-Mac-Mini:myHelloService sjrogers$ node --version
v13.3.0
SJR-Mac-Mini:myHelloService sjrogers$ npm --version
6.13.2
SJR-Mac-Mini:myHelloService sjrogers$ aws --version
aws-cli/2.0.35 Python/3.7.4 Darwin/19.6.0 botocore/2.0.0dev39
SJR-Mac-Mini:myHelloService sjrogers$ serverless --version
Framework Core: 1.77.1
Plugin: 3.6.18
SDK: 2.3.1
Components: 2.33.1
SJR-Mac-Mini:myHelloService sjrogers$ sls invoke -f hello
{
    "statusCode": 200,
    "body": "{\n  \"message\": \"Go Serverless v1.0! Your function executed successfully!\",\n  \"input\": {}\n}"
}
SJR-Mac-Mini:myHelloService sjrogers$


