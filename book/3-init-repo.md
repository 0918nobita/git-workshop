# リポジトリを作成する

これから実際に git を使ってファイルの変更履歴を管理してみるわけですが、  
まず最初に**リポジトリ**を作成する必要があります。

リポジトリは「ファイルの過去の状態を記録する貯蔵庫」です。  
git の管理下にあるファイルを過去の状態に戻せるのは、この貯蔵庫が持っている過去の状態のファイルを取得できるという機能のおかげです。

ちなみに、テキスト以外の形式のファイル (バイナリ、画像等) でも管理できます。

### ローカルでリポジトリを作成する

**【やること1】** 以下のコマンドを実行して、ローカルにリポジトリを作成してください。

```bash
$ mkdir practice-repo
$ cd practice-repo
$ git init
Initialized empty Git repository in <path>
```

(補足) **コマンドの形式**

```bash
git init [ディレクトリ]
```

ディレクトリを指定しなかった場合、カレントディレクトリが新規のリポジトリとして初期化されます。

この際 ``.git`` ディレクトリが作成されますが、過去の状態のファイルや git 内部で使用するキャッシュ、詳細設定等を書き込むためのディレクトリなので、誤って削除しないように注意が必要です。
