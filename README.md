# serverless-python-langchain-example

## 開発手順

Python の仮想環境の作成と有効化

```console
python -m venv .venv
. .venv/bin/activate
```

## デプロイ手順

Serverless Framework とプラグインのインストール

```console
npm install -g serverless@3.33.0
sls plugin install -n serverless-python-requirements@6.0.0
```

デプロイ

```console
sls deploy
```
