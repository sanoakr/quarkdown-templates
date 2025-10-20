# Quarkdown Templates

このリポジトリは、[Quarkdown](https://github.com/iamgio/quarkdown) のテンプレート集です。

## 含まれるテンプレート

### 卒業論文テンプレート (`grad_template.qd`)

龍谷大学先端理工学部数理・情報科学課程向けの卒業論文テンプレートです。

**特徴:**

- A4サイズ、余白1.5cm
- 日本語対応
- セクション番号の自動採番（第1章、第2.1節など）
- 表、図、数式、引用の自動番号付け
- タイトルページ機能付き

**使用方法:**

```bash
quarkdown c grad_template.qd
```

ライブプレビューを有効にする場合:

```bash
quarkdown c grad_template.qd -p -w
```

## TODO
- ページ番号表示
- 謝辞・参考文献・付録の目次への反映
- Mermaid 図の相互リファレンス
- 日本語の参考文献を追加


## 必要な環境

- [Quarkdown](https://github.com/iamgio/quarkdown) がインストールされていること

## ディレクトリ構成

```text
.
├── grad_template.qd          # 卒業論文テンプレート
├── references.bib            # 参考文献ファイル
├── image/                    # 画像ファイル用ディレクトリ
└── output/                   # 出力先ディレクトリ
```

## 参考リンク

- [Quarkdown 公式リポジトリ](https://github.com/iamgio/quarkdown)
- [Quarkdown 公式Wiki](https://github.com/iamgio/quarkdown/wiki)
