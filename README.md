# NotebookLM Automation

> **注意**: このドキュメントと拡張機能は AI アシスタント "Cline" によって生成されました。

## 概要

このブラウザ拡張機能は、NotebookLM での Web ページの参照を自動化するために開発されました。現在開いているタブの URL を NotebookLM に自動的に追加することができます。

## 機能

- キーボードショートカットで自動化を開始
- 現在のタブの URL を自動取得
- NotebookLM での新規ノート作成を自動化
- Web ページの参照を自動追加

## インストール方法

1. このリポジトリをクローン
```bash
git clone https://github.com/yourusername/test-cline.git
```

2. 依存パッケージをインストール
```bash
npm install
```

3. ビルドを実行
```bash
npm run build
```

4. Chrome の拡張機能管理画面を開く
5. 「デベロッパーモード」を有効化
6. 「パッケージ化されていない拡張機能を読み込む」をクリック
7. ビルドされた `dist` フォルダを選択

## 使い方

1. Chrome で任意の Web ページを開く
2. キーボードショートカット `Ctrl+Shift+Y`（Windows/Linux）または `Cmd+Shift+Y`（Mac）を押す
3. 自動的に NotebookLM が開き、現在のページが参照として追加されます

## 開発

### 必要要件

- Node.js 16.x 以上
- npm 8.x 以上

### 開発用コマンド

```bash
# 開発用ビルド（ウォッチモード）
npm run dev

# プロダクションビルド
npm run build

# リント
npm run lint

# フォーマット
npm run format
```

## ライセンス

MIT License

## 貢献について

1. このリポジトリをフォーク
2. 新しいブランチを作成 (`git checkout -b feature/amazing-feature`)
3. 変更をコミット (`git commit -m 'Add some amazing feature'`)
4. ブランチにプッシュ (`git push origin feature/amazing-feature`)
5. プルリクエストを作成

## 問題報告

バグを見つけた場合は、GitHub の Issue トラッカーで報告してください。
