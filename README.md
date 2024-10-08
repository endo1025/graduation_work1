■サービス概要
日本の各都道府県ごとに、訪れた観光名所・お店・ホテルや撮影した写真をSNSとして投稿し、
旅行で訪れた内容を思い出として残すことができるCGMです。

■ このサービスへの思い・作りたい理由
私自身、今まで何度も旅行をしているが、あとから懐かしむことができるのは写真を見返す程度であとは記憶頼りです。
また、写真自体も時が流れるほど、どこに保管していたか管理できなくなってしまい、旅行の思い出も記憶から段々と薄れていってしまっています。
こういったことが起こらないように、旅行の思い出を残し、何年経った後からでも鮮明に思い出すことができるサービスを作りたいと思ったためです。

■ ユーザー層について
カップルや小さいお子さんがいる家庭を対象ユーザ層としています。
理由は下記2つです。
1.他のユーザー層に比べて旅行をする機会が多いため
2.様々な旅行の思い出をデータとして残し、後々みんなでそれらの旅行を懐かしんで欲しいため

■サービスの利用イメージ
ユーザーが日本のどこかへ旅行する度に、旅行内容をSNSに投稿することで、思い出としてデータに残すことができる。
また、他のユーザーからは旅行先の参考としておすすめの場所を参照することができる。

■ ユーザーの獲得について
現状考えられていません。

■ サービスの差別化ポイント・推しポイント
ログイン後のトップページに、各都道府県の形に切り取って写真を表示させることができる機能
ログイン後のトップページに、各都道府県に写真がスライドショー形式で表示される機能(投稿した写真が流れる)

■ 機能候補
＃MVP
・ユーザー登録
・ログイン
・記事投稿
・記事一覧
・いいね機能
・タグづけ
・マルチ検索
・画像加工・合成

＃本リリース
・チャット機能
・通知機能

■ 機能の実装方針予定
・都道府県の形を切り取った画像加工が本サービスのメインなので、この機能をAPIを使用して実装したいです。
※ImageMagickを使用したいと考えています。
・検索機能はStimulus Autocomplete（Rails7)を使用したいと考えています。


### 画面遷移図
https://www.figma.com/design/KSvBbw0BKFqFWdxAgqrWKM/%E7%94%BB%E9%9D%A2%E9%81%B7%E7%A7%BB%E5%9B%B3?node-id=0-1&t=tKHCGJIRbUjyt0KB-0

### ER図
![image](https://github.com/user-attachments/assets/88fdaef7-4e24-4e89-a298-9fbbdda2070f)

