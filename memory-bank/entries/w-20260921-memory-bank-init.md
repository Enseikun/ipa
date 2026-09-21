# memory-bank 初期ファイルの生成
- id: w-20260921-memory-bank-init
- tags: memory-bank,setup
- updated: 2026/09/21 20:50

## 要点
`.cursor/rules/10-memory-bank.mdc` と `.cursor/rules/20-self-improving.mdc` の追加を受け、
`memory-bank/` 配下に中核6ファイル（projectbrief / activeContext / productContext /
systemPatterns / techContext / progress）と `index.md`、および本entryを新規生成した。
内容は当時のプロジェクト実態（IPA情報処理安全確保支援士試験対策のレクチャーノート
作成プロジェクト、`A-1/` 26本完成・`A-2B/` 未着手）を反映している。

## 根拠
- 調査時点のディレクトリ構成: `A-1/` に26本のノート（第2〜12章）、`A-2B/` は空、
  `memory-bank/` は空ディレクトリとして存在。
- 一次情報源: `0.0_ガイドライン.md`、`0.1_試験範囲.md`、`0.2_出題傾向.md`、
  `0.3_優先順位.md`、`ipa_試験要綱_v5.6.pdf`（プロジェクトルート直下）。
- git status 上、`A-1/0.0_ガイドライン.md` が削除され、同名ファイルがルート直下に
  新規追加されていたため、コンテキストファイルの集約が既に進行していたと判断し
  `projectbrief.md` 等のリンクはルート直下のパスで記載した。
