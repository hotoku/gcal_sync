# gcal_sync

特定のカレンダーのスケジュールを、別のカレンダーに同期するアプリ。

## 動作概要
以下、コピー元となるカレンダーをFROM, コピー先となるカレンダーをTOとする。

1. FROMから、一定期間のスケジュール情報を取得
2. TOの、同期間のスケジュールを削除
3. 1.で取得したスケジュールの開始・終了時間・タイトルと同内容の予定をTOに登録

## todo

1. 例外が起こった時に通知する(以下のトークンの期限切れなどで定期的に発生するはず)
