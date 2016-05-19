## 情報セキュリティ論

#### 2016/05/19　第5回:Webの脆弱性  
- CSRF:トークン e.g.Cookie
対策: USB認証を加える．確認できるように秘密の情報を与える．もう一度Passwordを与える．  
- CAPTCHA: 人間にしか識別できない画像．視覚認証  

- ディレクトリトラバーサル  
- パラメータ操作 e.g.購入状況を暗号化なしで送信．改ざんできることを理解．parameter manipulation  
対策: プロキシ中継

#### 2016/05/19　第6回:対策技術  
アクセスコントロール *IAAA*  
- 識別 Identification e.g. ID入力  
- 認証 Authentication e.g. Password認証，指紋認証　　
- 認可 Authorization e.g. 権限管理  
- 責任 Accountability e.g. ログ管理  

認証メカニズム

- PIN: 4桁のパスワード（セキュリティ弱い）
- パスワード： 8桁英数ランダム  