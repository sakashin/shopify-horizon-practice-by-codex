# HIYORI — Horizon practice by Codex

HIYORIサンプルストア用のShopifyテーマ。StoreHero版Horizon upstream/v4.2.0をベースに、FigmaのHorizon UI Kitから構成しています。

## ストア

- 開発ストア: `horizon-practice-by-codex.myshopify.com`
- Figma: https://www.figma.com/design/hiLYiTiZrCWzHTneeNULS9
- 上流: https://github.com/StoreHero-StoreFront/shopify-sh-horizon/releases/tag/upstream%2Fv4.2.0

## 管理する内容

このリポジトリはテーマファイルを管理します。商品・コレクション・固定ページ・ブログ記事・メニュー・ポリシーはShopify管理画面で管理します。画像設定は当該開発ストアのShopify Filesを参照します。

Horizonのネイティブなhero、product-list、collection-list、media-with-content、featured-blog-postsとテーマブロックを使用しています。固定ページ・記事の補足スタイルは `assets/hiyori.css` にまとめています。

## 反映

Shopify管理画面 → オンラインストア → テーマ → GitHubから接続で、このリポジトリのテーマ用ブランチを選択します。まずテーマライブラリでプレビューを確認してください。GitHub接続後はテーマエディタからの変更も同期されるため、編集前に最新コミットを取得します。

## 確認

```sh
shopify theme check --path .
```

サンプルストアです。商品仕様・画像・価格は練習用データで、決済・配送条件や事業者情報の確定は別途必要です。ストアのパスワード保護を維持してください。
