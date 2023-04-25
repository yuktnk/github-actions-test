# GitHub Actionsのテスト
## 概要
Create-React-App製のアプリケーションで、GitHub Actionsを用いてビルド〜デプロイを行う
## 詳細
1. masterブランチへのマージをhookに、npm rub buildを実行する
2. 上記のbuildが終わったタイミングで、./buildディレクトリに生成された静的資材をGitHub Pagesへデプロイする

## 参考
- https://docs.github.com/ja/actions/automating-builds-and-tests/building-and-testing-nodejs