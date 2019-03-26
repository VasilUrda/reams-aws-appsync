# reams-aws-appsync

## Why is it needed?
When user is offline and mutations are happened, the aws-appsync package stores snapshot to local storage. And that snapshot is restored when user becomes online. This makes users confused about their works and they can think that they lost their works.

## How to update it?
aws-appsync is maintained by lerna so we should create our own package to use updated aws-appsync. We called it `reams-aws-appsync`

## What we have changed?
We have disabled the restoring snapshot code [Disable Snapshot Restore](https://github.com/realestateams/reams-aws-appsync/commit/c4beb436ea59df106e57667074d1843386900c95)

