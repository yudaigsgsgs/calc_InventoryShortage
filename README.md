# calc_InventoryShortage

## 設定
1. 仕入れ計算.exeフォルダの中に仕入れ計算.exeファイルがあるので、スタートにピン止め or タスクバーにピン止め or デスクトップにショートカットを作成してください。
2. .envファイルのSLACK_URLのダブルクオーテーションの内側を自身のSLACK_URLに書き換えて下さい。（必須ではないが利便性のため）

3. https://w1572504239-vx5393221.slack.com/apps/new/A0F7XDUAZ--incoming-webhook-     にアクセス
4. チャンネルへの投稿のチャンネルを選択から自分を選ぶ
5. Incoming webhook インテグレーションの追加をクリック
6. ページが切り替わるのでセットアップの手順のすぐ下のwebhook urlのurlをコピーしてください。
7. コピーしたrlを.envファイルをメモ帳で開いてダブルクオーテーションの間にペーストしてください。ctrl+sで保存して閉じてください。
以上で設定は終了です。


## 使い方
1. 仕入れリスト計算.exeを起動
2. 案内に沿って進める
3. 仕入れ計算ver2フォルダに補充リスト.xlsxがあるので確認してください。


## 補足
1. ダウンロードするファイルの保存先はダウンロードフォルダにしてください。
2. フルフィルメントレポートはcsv, txtどちらでも問題ありません。
