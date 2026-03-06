# Stress-Buster-legal

Stress Buster の法務サイト用リポジトリです。GitHub Pages ではルートの `index.html` を入口として、各法務文書を個別ページで配信する構成にしています。

## Files

- `index.html`: 法務サイトのホーム
- `privacy.html`: プライバシーポリシー
- `terms.html`: 利用規約
- `tokusho.html`: 特定商取引法に基づく表記
- `assets/styles.css`: 共通スタイル
- `.nojekyll`: GitHub Pages の Jekyll 処理を無効化するためのファイル
- `legal_app_summary.md`: 法務文面作成の前提資料

## GitHub Pages

1. GitHub の対象リポジトリを開く
2. `Settings` > `Pages` を開く
3. `Build and deployment` の `Source` を `Deploy from a branch` にする
4. `Branch` を公開したいブランチ、フォルダを `/ (root)` にする
5. 保存後、公開URLで `index.html` が配信されることを確認する

## Notes

- Jekyll テーマやビルド設定は使っていません。
- カスタムドメインを使う場合は、別途 `CNAME` を追加してください。
