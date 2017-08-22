# Icon API
各種サービスのアイコンにリダイレクトするURLを提供するAPIです。

## `/icon/misskey/:domain/:screen_name`

misskey.`:domain`に存在する@`:screen_name`のアイコンへリダイレクトします。

利用例: `<img src="https://api.surume.tk/icon/misskey/xyz/syuilo">`  
<img src="https://api.surume.tk/icon/misskey/xyz/syuilo" height=60>

:warning: `:domain`はホワイトリスト制です。詳しくはお問い合わせください。

## `/icon/twitter/:screen_name`

Twitterに存在する@`:screen_name`のアイコンにリダイレクトします。

利用例: `<img src="https://api.surume.tk/icon/twitter/imascg_stage">`  
<img src="https://api.surume.tk/icon/twitter/imascg_stage" height=60>

:warning: Twitterの仕様変更や、レートリミットの制限などにより、リダイレクトに失敗する場合があります。

### `/icon/twitter/id::id`

Twitterに存在するユーザーID`:id`のアイコンにリダイレクトします。

利用例: `<img src="https://api.surume.tk/icon/twitter/id:3220191374">`
<img src="https://api.surume.tk/icon/twitter/id:3220191374" height=60>

:warning: Twitterの仕様変更や、レートリミットの制限などにより、リダイレクトに失敗する場合があります。
