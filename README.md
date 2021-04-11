# shop-maker


## ■プロジェクト概要
ECサイト開発用の、カスタム可能テンプレートサイト開発
#### マスタ管理
https://docs.google.com/spreadsheets/d/12S9ADpyVIUlXjXIYzQ0he9vYCn8XqQZvturFyerhGU0/edit#gid=151679123
## ■タスク管理
Jira

https://shop-maker.atlassian.net/jira/software/projects/SHOP/boards/1

## ■version
JavaSE:16

springframework.boot:2.4.4

Spring Tool Suite 4: 4.3.1.RELEASE

Node: 14.16.0

TypeScript: 4.2.3

## ■環境構築手順

#### jdk最新化
https://shop-maker.atlassian.net/jira/software/projects/SHOP/boards/1?selectedIssue=SHOP-2



#### nodeのinstall
[nodeの公式](https://nodejs.org/en/download/)より、version: 14.16.0(推奨 2021/04/07)をinstall

#### packageのinstall
```
cd /client
npm install --save
```

#### TypeScriptのversionをワークスペースの設定に変更.
.vscode/setting.json

```
{   
    ...
    "typescript.tsdk": "./client/node_modules/typescript/lib",
    ...
}
```
