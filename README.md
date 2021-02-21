## マイグレーション

1. `diesel setup`でdiesel.tomlを作成する。
2. `diesel migration generate users`でマイグレーションファイル作成。
3. `diesel migration run`でテーブル作成及び、schema.rsの生成(.envに接続を定義する)