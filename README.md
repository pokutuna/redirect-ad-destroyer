chrome-CaptureForcedRedirect
===

強制リダイレクト広告の報告をいくつか受けて作成

https://chrome.google.com/webstore/detail/captureforcedredirect/lbahfihialbndmglcoibiblpddnconea

## 使い方

- 悪い広告が出そうなページを開く
- 拡張を起動する
  - 赤くなれば動作中
- 放ったらかす
- 別のページへ遷移したときに直前のページの内容を保存してくれます


## 何をしているか

- 毎秒以下の内容をメモリ上へ保存する
  - mhtml(表示確認要)
  - json(ページ中の各 frame の URL と html を書き出したもの)
- 起動した時点の URL から別の URL へ遷移したときに直前の内容を書き出す
  - ユーザの操作による遷移でも保存します
- 毎分ページをリロード
  - 強制リダイレクト広告は低い確率で表示され、ページ表示から数十秒経ってリダイレクトする動作が見られるため

## 注意
- 出力した内容には閲覧者の個人情報や認証情報などが含まれる場合があるので共有にご注意ください
