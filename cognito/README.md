## ユーザーを管理する（Amazon Cognito）

ユーザーアカウントを管理するために、Amazon Cognito ユーザープールを作成する。顧客が新規ユーザーとして登録し、電子メール アドレスを確認し、サイトにサインインできるページを展開する。

![](./readme-image/Serverless_Web_App_LP_assets-03.png)

### ユーザープールの作成

- Cognito ユーザープールを選択しサインインオプションにユーザー名を選択したら次へ。

<img src="./readme-images/userpool_step1.png" width="500px">

- MFAなしを選択しあとはデフォルトのままで次へ。

<img src="./readme-images/userpool_step2.png" width="500px">

- デフォルトのままで次へ。

<img src="./readme-images/userpool_step3.png" width="500px">

- SES で検証済みのメールアドレスを入力して次へ。

<img src="./readme-images/userpool_step4.png" width="500px">

- ユーザープール名、アプリケーションクライアント名を入力して次へ。

<img src="./readme-images/userpool_step5.png" width="500px">
