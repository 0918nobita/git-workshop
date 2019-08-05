# RCC Git 勉強会 2019

### 参加準備

- 持参する PC に git を導入する (導入方法については [環境構築](0-env.md) を参照)
- 可能な限りでいいので、この資料を読み進めて予習しておく

### 当日の流れ

原則、このページに載っている内容を先頭から確認していく形式で進めていきます。  
【やること(通し番号)】と記載してある箇所については、  
実際に番号順に git を操作して動作を確かめるようにしてください。

* 環境構築の確認
* [git の基礎知識](1-basics.md)
* [git の初期設定](2-initial-settings.md)
* [リポジトリの作成](3-init-repo.md)
* [ステージ / コミット](4-commit.md)
* [SSH 鍵の生成・登録](6-ssh-keygen.md)
* [リモートリポジトリの作成・登録](7-prepare-remote.md)
* [プッシュ](8-push.md)
* [クローン](9-clone.md)
* [ブランチとチェックアウト](10-branch.md)
* [マージリクエスト / マージ](11-merge.md)
* [イシュー](12-issue.md)
* [総会文書](13-soukai.md)

### 余裕のある人向け

* `.gitignore` を用いて、特定のファイル/ディレクトリを管理対象から外す https://qiita.com/inabe49/items/16ee3d9d1ce68daa9fff
* ``git add -p`` コマンドで部分的にコミットする https://qiita.com/cotton_desu/items/bf08ac57d59b37dd5188
* ``git rebase -i`` コマンドで複数のコミットをまとめる https://qiita.com/tatetate55/items/7a822a3246df79d693b8
* ``git stash`` コマンドで変更差分をコミットせずに一時退避する https://qiita.com/keisuke0508/items/4ad7caf544b1ad631fd7
* GPG を用いて署名付きでコミットする https://qiita.com/ykgeek/items/98ecfd0f3e22cea7eb10
