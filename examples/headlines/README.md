# DataFire - News Headlines

Send yourself an e-mail with the latest items from a few RSS feeds.

```
datafire integrate gmail cnn npr nytimes
datafire authenticate gmail --generate_token
# Follow the command-line prompts

datafire run headlines
```

## Serverless
Runs every day by default. You can change this in `serverless.yml`

```
serverless deploy -v
```
