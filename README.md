# Host Web Service with AWS Lambda

More info here:  [https://coderecipe.ai/architectures/1453356](https://coderecipe.ai/architectures/1453356)

### Prerequisites
```  
npm install serverless  
```  
Make sure you have AWS access key and secrete keys setup locally, following this video [here](https://www.youtube.com/watch?v=KngM5bfpttA)


### Download the code locally

```  
serverless create --template-url https://github.com/CodeRecipe-dev/serverless-graphql --path serverless-graphql  
```

### Deploy to the cloud
 
```
cd serverless-graphql

npm install

serverless deploy --stage <your-stage-name>
```
