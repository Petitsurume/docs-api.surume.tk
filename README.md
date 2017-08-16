# api.surume.tk 公開APIについて
api.surume.tkでは、一部のエンドポイントを一般利用者向けに開放しています。
ここでは、一般利用者向けに開放しているAPIの利用方法を紹介します。

## ご注意
api.surume.tk は、不定期にデプロイやメンテナンス、サーバー自体の問題などでサービス提供を停止することがあります。
また、利用者に告知せずにAPIのエンドポイントを変える場合もあります。
利用する場合は、その点をご理解ください。

## Icon API
各種サービスのアイコンにリダイレクトするURLを提供するAPIです。

### `/icon/misskey/:domain/:screen_name`

misskey.`:domain`に存在する@`:screen_name`のアイコンへリダイレクトします。

:warning: `:domain`はホワイトリスト制です。詳しくはお問い合わせください。

### `/icon/twitter/:screen_name`

Twitterに存在する@`:screen_name`のアイコンにリダイレクトします。

:warning: Twitterの仕様変更や、レートリミットの制限などにより、リダイレクトに失敗する場合があります。
