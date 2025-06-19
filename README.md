# ギャルゲーで学ぶ英語

日本の美少女ゲームファンのための実践的英語教科書

## 概要

このプロジェクトは、日本のギャルゲー・美少女ゲームを愛する高校生が、海外のフォーラムやコミュニティで英語でコミュニケーションできるようになることを目指した教科書です。

## ローカル開発

### 必要環境

- Python 3.8以上
- pip

### セットアップ

```bash
# リポジトリをクローン
git clone https://github.com/your-username/galge-english.git
cd galge-english

# 仮想環境を作成（推奨）
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate

# 依存関係をインストール
pip install -r requirements.txt
```

### ローカルサーバーの起動

```bash
mkdocs serve
```

ブラウザで http://127.0.0.1:8000 にアクセスすると、教科書を閲覧できます。

### ビルド

```bash
mkdocs build
```

`site/` ディレクトリに静的サイトが生成されます。

## デプロイ

このプロジェクトはGitHub Actionsを使用して自動的にGitHub Pagesにデプロイされます。
`main`または`master`ブランチにプッシュすると、自動的にビルドとデプロイが実行されます。

## ライセンス

Copyright © 2024 Galge English Project