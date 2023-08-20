# wildrydes-site

wildrydes-site

<!-- @import "[TOC]" {cmd="toc" depthFrom=2 depthTo=6 orderedList=false} -->

<!-- code_chunk_output -->

- [① 静的ウェブホスティング](#1-静的ウェブホスティングamplifyreadmemd)
- [② ユーザー管理](#2-ユーザー管理cognitoreadmemd)
- [③ サーバーレスバックエンド](#3-サーバーレスバックエンド)
- [④ RESTful API](#4-restful-api)
- [参考資料](#参考資料)

<!-- /code_chunk_output -->

![](/doc/Architecture.drawio.png)

#### [① 静的ウェブホスティング](./amplify/README.md)

AWS Amplify は、HTML、CSS、JavaScript、およびユーザーのブラウザに読み込まれたイメージファイルを含む静的なウェブリソースをホストします。

#### [② ユーザー管理](./cognito/README.md)

Amazon Cognito は、バックエンド API を保護するためのユーザー管理機能と認証機能を提供します。

#### ③ サーバーレスバックエンド

Amazon DynamoDB は、API の Lambda 関数によってデータを格納できる永続レイヤーを提供します。

#### ④ RESTful API

ブラウザで実行される JavaScript は、Lambda と API Gateway を使用して構築されたパブリックバックエンド API からデータを送受信します。

#### 参考資料

- [サーバーレスのウェブアプリケーションを構築する](https://aws.amazon.com/jp/getting-started/hands-on/build-serverless-web-app-lambda-apigateway-s3-dynamodb-cognito/)
