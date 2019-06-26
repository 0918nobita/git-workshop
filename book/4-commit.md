# ステージ / コミット

リポジトリが準備できたので、実際にファイルを編集した上で、その差分を記録する「ステージ」「コミット」機能を使ってみます。

### 「ステージする」とは

記録する対象となる変更内容を指定することを指します。

### 「コミットする」とは

メッセージを入力した上で、ステージされた変更を記録することを指します。

**【やること2】** ``practice-repo`` ディレクトリ内に ``README.md`` ファイルを作成して、以下の内容を書き込んで保存してください。

```markdown
# 練習用リポジトリ
```

**【やること3】** 以下のコマンドを実行して、リポジトリ内のファイルの変更状況を確認してください。

```bash
$ git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)

	README.md

nothing added to commit but untracked files present (use "git add" to track)
```

**【やること4】** 以下のコマンドを実行して、``README.md`` をステージしてください。

```bash
$ git add README.md
```

**【やること5】** ``git status`` コマンドを実行して、【やること4】の操作によって ``README.md`` をステージできていることを確認してください。

```bash
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)

	new file:   README.md
```

**【やること6】** 以下のコマンドを実行して、``README.md`` での変更をコミットしてください。

```bash
$ git commit -m ":tada: Initial commit"
```
