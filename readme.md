デプロイする

```
$ sls deploy
```

削除する

```
$ sls remove
```

動作確認する

```
$ sls invoke --function hello -p event.json
```

東京リージョンにデプロイする

serverless.ymlに以下を設定する

```
provider:
  name: aws
  runtime: nodejs8.10
  stage: beta
  region: ap-northeast-1
```
