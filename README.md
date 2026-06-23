# TENTO AI TEST

TENTOのAI性能テスト用リポジトリです。

## 概要

このリポジトリでは、AIアシスタントがワークショップ用の教材やポートフォリオサイトを生成するテストを行っています。

## プロジェクト一覧

- `01_test_portfolio/` - ポートフォリオサイト（HTML + Tailwind CSS）

## 公開手順（GitHub にアップロードする方法）

以下の手順をターミナル（コマンドライン）で1つずつ実行してください。

### 1. ターミナルを開く
VS Code で `Ctrl + @` またはターミナルメニューから「新しいターミナル」を開きます。

### 2. ディレクトリに移動
```bash
cd /Users/shiozawatakumi/Documents/07_TENTO/TENTO_AI_TEST
```

### 3. Git を初期化
```bash
git init
```

### 4. すべてのファイルをステージング
```bash
git add .
```

### 5. 最初のコミット
```bash
git commit -m "初回コミット：ポートフォリオサイトとREADME"
```

### 6. GitHub で新しいリポジトリを作る
1. ブラウザで https://github.com にログイン
2. 右上の「+」→「New repository」をクリック
3. Repository name に `TENTO_AI_TEST` と入力
4. Public（パブリック）を選択
5. 「Create repository」をクリック

### 7. GitHub とローカルを接続
GitHub の画面に表示される「…or push an existing repository from the command line」の下にあるコマンドをコピーしてターミナルで実行します。

例：
```bash
git remote add origin https://github.com/あなたのユーザー名/TENTO_AI_TEST.git
git branch -M main
git push -u origin main
```

※ `あなたのユーザー名` は自分のGitHubユーザー名に置き換えてください。

### 8. 完了！
ブラウザで GitHub のリポジトリページを開き、ファイルがアップロードされていることを確認します。

## 注意点
- GitHub に初めて接続する場合は、ユーザー名とパスワード（またはトークン）の入力を求められます。
- GitHub CLI を使うともっと簡単にできますが、ここでは基本の手順を紹介しています。
