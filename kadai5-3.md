## 外部APIの呼び出しのミニレポート
### Q3-1. 郵便番号APIについて説明せよ。
* エンドポイントと機能
　* https://zipcloud.ibsnet.co.jp/api/searc
  * 郵便番号を検索して都道府県、市区町村名、町域名を表示する
* リクエストとレスポンスのフォーマット
　* リクエストはGET
　* レスポンスはJSON
### Q3-2. 各自で調査したAPIについて説明せよ。
* APIの名称と参照URL
　* Advice Slip JSON API
  * https://api.adviceslip.com/#endpoint-random
* エンドポイントと機能
　* https://api.adviceslip.com/advice/{slip_id}
　* 入力した数字からアドバイスを検索し表示する
* リクエストとレスポンスのフォーマット
　* リクエストはGET
　* レスポンスはJSON
### Q3-3. 感想
* 今回の課題で苦労したこと
　* WebAPIを調べて使い方を理解したこと
* 演習を通して理解できたこと
　* APIを呼び出した結果の表示の仕方など
* Web APIの利便性や課題など
　* 利便性は外部システムを簡単に使用できるところ
  * 課題はオフライン時に使用できないところ
