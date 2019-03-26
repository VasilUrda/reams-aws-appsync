![AWS AppSync](https://s3.amazonaws.com/aws-mobile-hub-images/awsappsyncgithub.png)

## [AWS AppSync](https://aws.amazon.com/appsync/) JavaScript SDK

 This SDK can be used with the Apollo JavaScript client found [here](https://github.com/apollographql/apollo-client). Please log questions for this client SDK in this repo and questions for the AppSync service in the [official AWS AppSync forum](https://forums.aws.amazon.com/forum.jspa?forumID=280&start=0).

[![lerna](https://img.shields.io/badge/maintained%20with-lerna-cc00ff.svg)](https://lernajs.io/)
![npm](https://img.shields.io/npm/dm/aws-appsync.svg)


package | version
--- | ---
reams-aws-appsync | ![npm](https://img.shields.io/npm/v/aws-appsync.svg)
aws-appsync-react | ![npm](https://img.shields.io/npm/v/aws-appsync-react.svg)


## Installation    
#### npm    

```
npm install --save reams-aws-appsync
```

#### yarn    
    
```
yarn add reams-aws-appsync
```

## Why is it needed?
When user is offline and mutations are happened, the aws-appsync package stores snapshot to local storage. And that snapshot is restored when user becomes online. This makes users confused about their works and they can think that they lost their works.

## How to update it?
aws-appsync is maintained by lerna so we should create our own package to use updated aws-appsync. We called it `reams-aws-appsync`
This repo will be removed when aws-appsync fixed above issue.

## What we have changed?
We have disabled the restoring snapshot code [Disable Snapshot Restore](https://github.com/realestateams/reams-aws-appsync/commit/c4beb436ea59df106e57667074d1843386900c95)

