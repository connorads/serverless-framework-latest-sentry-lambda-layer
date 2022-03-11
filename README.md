# Serverless Framework + Latest Sentry Lambda Layer

```sh
➜ npm run deploy       

> serverless-framework-latest-sentry-lambda-layer@1.0.0 deploy
> serverless deploy


Deploying serverless-framework-latest-sentry-lambda-layer to stage dev (us-east-1)

✖ Stack serverless-framework-latest-sentry-lambda-layer-dev failed to deploy (2s)
Environment: darwin, node 16.13.1, framework 3.7.4 (local), plugin 6.1.5, SDK 4.3.2
Credentials: Local, "default" profile
Docs:        docs.serverless.com
Support:     forum.serverless.com
Bugs:        github.com/serverless/serverless/issues

Error:
User: arn:aws:sts::1234567890:assumed-role/AWS_Something_Stuff/user.name@email.com is not authorized to perform: lambda:ListLayerVersions on resource: arn:aws:lambda:us-east-1:943013980633:layer:SentryNodeServerlessSDK because no resource-based policy allows the lambda:ListLayerVersions action
```
