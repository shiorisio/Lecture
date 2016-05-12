## 情報セキュリティ論

#### 2016/05/12　第4回: システムにおける脆弱性  
- 脆弱性: 主にプログラムのバグ(e.g.バーコードで本の貸出，人のを借りればいくらでも借りれる．)  
- Exploit: セキュリティ侵害の目的で脆弱性を用いること．  

- Full Disclosure  
- 0-day: 未知の脆弱性  
- CVE (Common Vulnerabilities and Exposure): 脆弱性の標準化  
- CWE (Common Weakness Enumeration): 攻撃の種類  

- Buffer Overflow: 入力文字制限がある中で制限以上の入力をし破壊する．  
Q: Bufferとは？ 一時的な記憶容量 （e.g. 机）  
Q: ヒープは？ 一時的にではなくずっと（e.g. 本棚）  

- SQLインジェクション: バインドで決められた型しか入れない．  
- XSS対策:  
  Black list: 悪いものを定義  
  White list: 良いもの
  Escaping: 文字列処理  
  プロキシでの中継処理
