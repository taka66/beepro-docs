# Terminology
|Word|Description|
|----|-----------|
|beepro|物理的に同一のコードベースを複数人で群がって同期的に開発を行う|
|bee| Developers who using beepro |
|honey source|honeycomb上に存在しているコードベース|
|honeycomb|beeproが適応されているコードベースを管理するサーバー|
|dancer|beeの行った変更をhoneycombに対して通知する各IDEのプラグイン|
|nectar|各beeのローカルに存在しているコードベース|


# Stories
## Be able to apply beepro
1. Beeはブランチを切る（必要に応じて）みんぷろは関与しない
2. Beeは みんぷろモードをオンにする
3. Beeは 対象のブランチ名を入力する（デフォルト値は現在のブランチ名）
4. プラグインからHoneyCombにブランチ名、レポジトリのパスを知らせる
5. HoneyCombは該当レポジトリ、ブランチのHoney Sourceが存在しないので、ダウンロードをする
6. プラグインは該当のHoney Sourceとのハンドシェイクを開始する

## Be able to join existing beepro
1. Beeはブランチを切る（必要に応じて）みんぷろは関与しない
2. Beeは みんぷろモードをオンにする
3. Beeは 対象のブランチ名を入力する（デフォルト値は現在のブランチ名）
4. プラグインからHoneyCombにブランチ名、レポジトリのパスを知らせる
5. HoneyCombは該当レポジトリ、ブランチのHoney Sourceが存在しているので、ダウンロードをしない
6. プラグインは該当のHoney Sourceとのハンドシェイクを開始する

## Be able to synchronize nectar ( file contents change )

## Be able to synchronize nectar ( file operation - making new file, delete file )
