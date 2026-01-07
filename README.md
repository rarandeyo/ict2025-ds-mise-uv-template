# ict2025-ds-mise-uv-template

## 概要
データ・サイエンス社会応用論等で利用するcondaのPython環境をmise uvを使って簡単にでセットアップするための非公式テンプレート

利用は完全に自己責任です。

## 事前準備
- mise をインストールしていない場合は [公式ガイド](https://mise.jdx.dev/getting-started.html) を参照してセットアップする。


## Usage
セットアップ
- Trust: `mise trust .`
- Install tools: `mise install`
- Sync deps: `mise run sync`

リントとフォーマット
- Lint: `uv run ruff check`
- Format: `uv run ruff format`

仮想環境の削除
- Remove env: `rm -rf .venv`

