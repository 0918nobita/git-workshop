# git の初期設定

### ユーザー情報を登録する

```bash
$ git config --global user.name "<ユーザーネーム>"
$ git config --global user.email "<メールアドレス>"
```

### git から呼び出すエディタを指定する

デフォルトで nano が起動してしまう環境が存在するので必ず確認しておいてください。

Vim でいいと思います。

Windows 環境を使用している方は、Git のインストール時に選択したエディタを設定してください。

```bash
$ git config --global core.editor "vim"
```

### 現在の設定を確認する

```bash
$ git config --list
```
