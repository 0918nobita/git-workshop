# リポジトリを作成する

## ローカルでリポジトリを作成する

```bash
$ mkdir practice-repo
$ cd practice-repo
$ git init
Initialized empty Git repository in <path>
```

**コマンドの形式**

```bash
git init [ディレクトリ]
```

ディレクトリを指定しなかった場合、カレントディレクトリが新規のリポジトリとして初期化される。

この際 ``.git`` ディレクトリが作成されるが、git 内部で使用するキャッシュや詳細設定を書き込むためのでディレクトリなので、誤って削除しないように注意が必要。
