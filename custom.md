# カスタム要素

- [color scheme](#color-scheme)
- [Pagination](#pagination)

## Color Scheme

サイトアクセス時に自動的にローカルストレージからカラーテーマを取得して、テーマを設定します。

### 関数

| 名前 | 説明 |
| ---- | ---- |
| getTheme | 現在のカラーテーマを取得する |
| setThemeAndStore | カラーテーマを設定する |

## Pagination

前のページや次のページのナビゲーションボタンを実装します。

| 項目 | 説明 | デフォルト |
| ---- | ---- | ---- |
| pagination_prev_enabled | 前ページリンクの表示可否 | true |
| pagination_next_enabled | 次ページリンクの表示可否 | true |
| pagination_prev_page | 前ページの URL を手動指定 | auto |
| pagination_next_page | 次ページの URL を手動指定 | auto |
| pagination_exclude | フラットページリストへの登録除外 | false |

例：`docs/index.md`

```md
---
nav_order: 1
permalink: /docs
title: はじめに
pagination_exclude: false
---

# はじめに

サンプルです。
```
